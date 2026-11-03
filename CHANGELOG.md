# 1.0.2 (GoHighLevel fork, 3rd November 2026)

- Synced with upstream rtmigo/schedulers_dart `dev` (1.0.2)
- Kept the GHL change: `lib/schedulers.dart` exports the task types from `b_base.dart` (except `CancelFunc` and `QueueExt`), `c_concurrent.dart` and `c_rate_limiting.dart`
- Dart SDK constraint widened to `>=2.18.0 <4.0.0`
- `PriorityTask` constructor uses super-parameters; behaviour unchanged

# 1.0.2

- Minor fixes

# 1.0.1 

- Added `ParallelScheduler`
- Results of tasks are now `await`ed by the schedulers
- Result of `GetterFunc` changed from `<R>` to `FutureOr<R>`
- Dart SDK version requirements increased to 2.18
- Added example of basic usage of `RateScheduler`

# 0.3.1

- Added `TimeScheduler`

# 0.1.0

- Initial release
