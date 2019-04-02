# pj1
one new line
library(ggplot2)
df <- data.frame(Titanic)
ggplot(df, aes(x = Survived, fill = Class)) +
  geom_bar(position = "dodge")
ggplot(df, aes(x = Survived, y = Freq, fill = Class)) +
   geom_bar(stat = "identity", position = "dodge")