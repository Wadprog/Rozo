<div 
style="font-size:1.1rem;">

# Rozo-Bolet

> A lottery for the community.

## About.

Rozo-Bolet is an every 20 minutes lottery application that allows registered users to bet on a single or a set of numbers.

## How it works.

Every 20 mins the application let users bet on different numbers and reward them if they guessed some or all the winning numbers correctly. This operation happen in 2 phase recurrently every 20 mins. The two phases are:

1. _The Open bet phase_
2. _The close bet phase_

## The Open bet Phase.

The open bet phase will last 15 mins were users can place, change or cancel their bets. Users are allowed to bet as many time as they want with either one number or a set of number.

## The close bet phase.

In this phase no more bet can be placed ,changed or canceled by the user. Three process will happen:

1. The winning numbers will be drawn.
2. The wining prize will be calculated.
3. Winners balance will be updated base on the amount they won.

### How are the winning numbers are drawn.

The winning numbers will be drawn randomly, however it will take into account calculating for the numbers offering less winning possibility.

### How is the winning prize calculated

The winning prize the sum of all the bets made during the previous phase plus the _claimable_ portion of any unclaimed prize in the previous sessions.

### How are users balance will be updated.

Base on how much a user played for and the place in which their numbers match with the winning numbers. we calculate an amount which is considered their winning amount and add it to their balance.

### How to win

To win, one of the numbers you played must match the winning numbers.

Once we draw the winning numbers, This winning prize is divided among all the players which played for at least one of the drawn numbers.

The order in which the winning number set the percentage of the winning price that will be allocated for the players who played that number. The first number to be drawn will have 50% of the winning price the second 30% and the third 20%.

The total reserved for each number is then split among the winners depending of how much they invested in this number.

#### How we calculate each individual players price.

- First we calculate the average played for a given number. By adding up all the money played on the number then divide it by the amount of players who played that number.

- Second the amount you bet for will determine the percentage of the average for you.

> Example. _Imagine the following scenario where:_

- John plays 10 for $40
- Jean plays 13 for $30
- Anne plays 10 for $20
- Betty plays 12 for $20

Now we have our announcement/(tirage), the wining prize is $200 USD and the wining number are in this order:

1. 10
2. 12
3. 13
   Therefore we will have 50% of the 200 USD For the players that played 10 ,
   Therefore we will have 30% of the 200 USD For the players that played 12 ,
   Therefore we will have 20% of the 200 USD For the players that played 13 ,

Since both John and Jean played 10 there are 100 USD available for them to share each one will have a prize depending on their initial investment. This

> How is the amount you win is calculated
> (Todo formula needed)

Unlike general bolet, rozo bolet will have several (tirage) per hour increasing the chance of one user to win.

```

## Features for a MVP.

```

- User can create and account.
- User can login and out to their account.
- User can play a set of numbers.
- User are notified if they won
- User's balance automatically change on wining .

```

## Technologies uses

```

This project uses [Feathers](http://feathersjs.com). An open source web framework for building modern real-time applications.

```

## Getting Started

> Getting up and running is as easy as 1, 2, 3.

1. Make sure you have [NodeJS](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed.
2. Install your dependencies

```

cd path/to/arg-automation
npm install

```

3. Start your app
```

npm start

```

## Testing

Simply run `npm test` and all your tests in the `test/` directory will be run.

</div>
```
