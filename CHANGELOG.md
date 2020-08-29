# Changelog

## Unreleased

- `actor.start` returns a channel rather than a channel and a pid.
- `actor.StartError` includes a case for the child crashing while
  initialising.
- `actor.Spec` has an `init_timeout` field which specifies how long the actor
  has to initialise.
- `process.make_*` functions have been renamed to `process.new_*`.
- `actor.Message` is no longer a public type.
- The `process` module gains the `run_receiver_forever` function.
- The `actor` module gains the `new` and `null_channel` functions.
- The `task` module has been created with the `Task` type and the `async`,
  `try_await`, and `await` functions.

## v0.0.1 - 2020-08-20

- Initial minimal release.