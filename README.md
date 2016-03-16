# berlin-clock-java

Berlin Clock in Java

[![Build Status](https://travis-ci.org/ryanb93/berlin-clock-java.svg?branch=master)](https://travis-ci.org/ryanb93/berlin-clock-java)
[![Code Coverage](https://img.shields.io/codecov/c/github/pvorb/property-providers/develop.svg)](https://codecov.io/github/pvorb/property-providers?branch=develop)

A Java project that converts 24H time into its berlin clock representation.

The time should be entered in this format: "HH:MM:SS".

To run:

    ./gradlew run "24H_TIME"

Example run:

    ./gradlew run "09:40:01"

  To run tests:

    ./gradlew tests

Clock representation:
-   "0" - Lamp is off
-   "R" - Red lamp is on
-   "Y" - Yellow lamp is on