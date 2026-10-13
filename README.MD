# ESEP Grade Calculator

A Go library that calculates a final course grade from assignments (50%), exams (35%), and essays (15%), then converts it to a letter grade (A 90+, B 80+, C 70+, D 60+, F below 60).

## Requirements

Go 1.24 or newer (https://go.dev/dl/). No other dependencies.

## Run the tests

The code lives in the `grade-calculator` folder (with a hyphen, not an underscore):

~~~bash
cd grade-calculator
go test -v ./...
~~~

## Check code coverage

~~~bash
cd grade-calculator
go test -cover ./...
go test -coverprofile=coverage.txt ./...
go tool cover -func=coverage.txt
~~~