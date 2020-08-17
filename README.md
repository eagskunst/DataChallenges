# DataChallenges
Code/Notebooks that resolve the challenges on https://platzi.com/blog/data_challenge/

## Directory structure

Directories are divided into challenges. Each directory also has a 'db' directory that have data files related to the challenge.

## Building

1. Create and start a virtualenv:

`virtualenv --python=python3.8 [venvname]`
`source [venvname]/bin/activate`

2. Install the dependencies:

`pip install -r requirements.txt`

3. Start jupyter's server:

`jupyter notebook`

## Challenges

### Challenge 1: Titanic

1. How many people were on the Titanic?
2. How many man and woman survived?
3. Top 10 age that survived and top 10 that did not
4. How many titles/charges where in the ship?
5. Total of the tickets prices in USD

### Challenge 2: StackOverflow questions and tags

1. How many tags are?
2. Top 10 asked tags
3. Top 5 most/least scored questions:
4. Tags by score's mean, max and min
5. Relation between words count in body and score (pending)