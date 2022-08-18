# Practicing reprex -----------------------------------------------------------------------------

# NOT A REPREX
library(tidyverse)
library(palmerpenguins)

penguins |> 
  select(species, body_mass_g, flipper_length_mm, year) |> 
  filter(species == "Chinstrap") |> 
  str_to_lower(species) |> 
  group_by(island) |> 
  summarize(mean(body_mass_g, na.rm = TRUE),
            mean(flipper_length_mm, na.rm =TRUE))


### Making a reprex ----------------------
# want to make sure that it is failing in the same way but is much more simple

library(tidyverse) 

warpbreaks |> 
  mutate(wool = str_to_lower(wool))

# copy all of the code in the clipboard and then run the reprex function

# Reprex with a synthesized data frame

library(tidyverse)

dogs <- tribble(~"dog", ~"count",
        "Golden Retreiver", 4,
        "Pug", 6,
        "German Shepard", 7)
dogs |> 
  mutate(dog = str_to_lower(dog))
