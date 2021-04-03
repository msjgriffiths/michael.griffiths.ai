# Testing

This is simply a test of GitHub Markdown support in `gh-pages`.

Let's see.

```R
library(tidyverse)

df <- data("mtcars")

df %>%
  ggplot(aes(cyl, hp)) +
  geom_point()
```

How about Python?

```python
import numpy as np

x = np.random.rand(100)
```

And Julia?

```julia
using Random

x = randn(10, 10)
```
