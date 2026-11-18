# Restaurant Hack

A small React app I made to find open tables during Dine Athens in April 2022.

## It doesn't work anymore

The campaign code (`DINEATHENS`) and the April 2022 dates are hard-coded, and
both have long expired. The iReserve endpoint still answers, but it no longer
returns anything useful for this event.

## What it did

You picked a table for two or four, and it checked Spondi, Sense, Zillers, CTC
and Ovio for every date left in the event, then showed each free time once.

## Running it

It's React 18 on Create React App:

```sh
npm install
npm start
```

The page still loads, but searches won't find anything.
