# Poker

Pick the best hand(s) from a list of poker hands.

See [wikipedia](https://en.wikipedia.org/wiki/List_of_poker_hands) for an
overview of poker hands.

## Running tests

Execute the tests with:

```bash
$ mix test
```

### Pending tests

In the test suites, all but the first test have been skipped.

Once you get a test passing, you can unskip the next one by
commenting out the relevant `@tag :pending` with a `#` symbol.

For example:

```elixir
# @tag :pending
test "shouting" do
  assert Bob.hey("WATCH OUT!") == "Whoa, chill out!"
end
```

Or, you can enable all the tests by commenting out the
`ExUnit.configure` line in the test suite.

```elixir
# ExUnit.configure exclude: :pending, trace: true
```

If you're stuck on something, it may help to look at some of
the [available resources](https://exercism.io/tracks/elixir/resources)
out there where answers might be found.

## Source

Inspired by the training course from Udacity. [https://www.udacity.com/course/viewer#!/c-cs212/](https://www.udacity.com/course/viewer#!/c-cs212/)

## Submitting Incomplete Solutions
It's possible to submit an incomplete solution so you can see how others have completed the exercise.
