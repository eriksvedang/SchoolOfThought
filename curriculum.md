# Lesson 1
Functor
  fmap over IO value
  defining your own Functor instance
  curried functions working on functors

# Lesson 2
Applicative
  pure
  <*>
  <*> vs <$>

  Using applicative for IO:
    myAction :: IO String
    myAction = (++) <$> getLine <*> getLine

Alternative
  Folding over a list of Maybe, using <|>

# Lesson X
Mapping and reducing

Foldable

Traversable

# Lesson Y
Monoids
MonadPlus
MonadZero?

# Lesson 3
Monads
Monad transformers

# Lesson 4
Semigroups

# Lesson 5
Free monads

# Lesson 6
Arrows
Category

# Lesson 7
Profunctor
Bifunctor

# Lesson 8
Comonad


