<dt-article>
<h1>Testing</h1>

<p>This is simply a test of GitHub Markdown support in `gh-pages`.</p>

<p>Let's see.</p>

<dt-code block language="r">
library(tidyverse)

df <- data("mtcars")

df %>%
  ggplot(aes(cyl, hp)) +
  geom_point()
</dt-code>

How about Python?

<dt-code block language="python">
import numpy as np

x = np.random.rand(100)
</dt-code>

And Julia?

<dt-code block language="julia">
using Random

x = randn(10, 10)
</dt-code>
</dt-article>
