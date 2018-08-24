# Omar SADEK - Tumlbr

## Summary

- [*Installation*](#installation)
- [*Question One Anagrams*](#question-one-anagrams)
- [*Question Two Boggle*](#question-two-boggle)

## Installation

Install vendors

```
$ git clone git@github.com:omarysadek/tumblr.git
$ cd tumblr/
$ composer update
```

## Question One: Anagrams

| Task          | Time   |
|---------------|--------|
| Conception    | ~7m    |
| Set up env    | ~10m   |
| Coding        | ~25m   |
| Documentation | ~5m    |
| Total         | ~50m   |

Running tests

```
$ vendor/bin/phpunit --group anagram
```

_Tests cases are written here => Tests\AnagramTest.php_

## Question Two: Boggle

| Task          | Time   |
|---------------|--------|
| Conception    | ~20m   |
| Coding        | ~2h30m |
| Documentation | ~5m    |
| Total         | ~3h    |

Running the game

```
$ php console.php boggle
```
> Please chose the size of the grid? 4
> How would like to generate the grid : 1) Manually 2) Randomly 1
> Please enter your grid, without space followed by | for each line
> here an exemple :
> ```
> 4x4 => ARTY|EAON|YSTD|ECIC
> ```
> : ARTY|EAON|YSTD|ECIC
> a r t y
> e a o n
> y s t d
> e c i c
>
> Please enter a word : arty
> arty => true
> Please enter a word : tony
> tony => true
> Please enter a word : notice
> notice => true
> Please enter a word : year
> year => true
> Please enter a word : stand
> stand => false
> Please enter a word : party
> party => false
> Please enter a word : stick
> stick => false
> Please enter a word : ^C

@toDo unit tests