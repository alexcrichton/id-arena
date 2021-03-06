# 2.0.1

Released 2019-01-09.

* Implemented `Ord` and `PartialOrd` for `Id<T>`.
* Added an `Arena::with_capacity` constructor.
* Added `Arena::next_id` to get the id that will be used for the next
  allocation.

# 2.0.0

Released 2018-11-28.

* Introduces the `ArenaBehavior` trait, which allows one to customize identifier
  types and do things like implement space optimizations or use identifiers for
  many arenas at once.
* Implements `Clone`, `PartialEq` and `Eq` for arenas.

# 1.0.2

Released 2018-11-25.

* `Id<T>` now implements `Send` and `Sync`
* The `PartialEq` implementation for `Id<T>` now correctly checks that two ids
  are for the same arena when checking equality.

--------------------------------------------------------------------------------

# 1.0.1

--------------------------------------------------------------------------------

# 1.0.0
