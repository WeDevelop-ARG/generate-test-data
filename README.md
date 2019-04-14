# Generates sets for testing

## Prerequisites

- Node (lts version recommended): https://nodejs.org/en/download.

## Install

Clone the repo and install dependencies:

```
npm install
```

## Available scripts

### Generate people

It generates a CSV file with a bunch of people. You can pass how many rows and how
many files you want to generate. By default, it'll create a single file with
1,000,000 to 1,500,000 of rows.

#### Usage

```
./generate-people.js [<NUM_FILES> [<MIN_ROWS> [<MAX_ROWS>]]]
```

#### Example

Using default values:
```
./generate-people.js
```

Generating two files:
```
./generate-people.js 2
```

Generating two files and more rows:
```
./generate-people.js 2 1500000 3000000
```
