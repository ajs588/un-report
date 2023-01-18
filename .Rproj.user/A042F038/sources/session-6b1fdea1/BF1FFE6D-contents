#Analyzen life expectancy and co2 emission versus po with gapminder
#date:
#Authors

# load packages
2+2
library("tidyverse")

# read in data for analysis 
gapminder_1997 <- read_csv("gapminder_1997.csv")

#plotting data for vizualization


ggplot(data=gapminder_1997) +
  aes(x=gdpPercap) +
  labs(x="GDP Per Capita") +
  aes(y= lifeExp) +
  labs(y="Life Expectancy (yrs)")+
  geom_point()+
  labs(title="Do people in wealthy countries live longer?")+
  aes(colour=continent)+
  scale_colour_brewer(palette = "Set1")+
  aes(size=pop/1000000)+
  labs(size="Population (in millions)")+
  aes(shape=continent)

#short handed ggplot
ggplot(data=gapminder_1997),
  aes(x=gdpPercap, y=lifeExp, color=continent, shape=continent, size=pop))+
  labs(x="GDP Per Capita", y="LifeExpectancy",
       title="Do People in Wealthy Countries live longer?",
       size="Population (in million)")+
  geom_point()

#read in all of the data from gapminder (>1997!)
gapminder_data <- read_csv("gapminder_data.csv")
View(gapminder_data)
dim(gapminder_data)
head(gapminder_data)
tail(gapminder_data)
ggplot(data = gapminder_data) +
  aes(x=year, y=lifeExp, color=continent, group=country) +
  geom_line()    

#learn about data
str(gapminder_data)

ggplot(data = gapminder_1997) +
  aes(x=continent, y=lifeExp, color=continent) +
  geom_violin() +
  geom_jitter(aes(size=pop))


#histogram
ggplot(gapminder_1997)+
  aes(x=lifeExp)+
  geom_histogram(bins = 20)+
  theme_classic()
   
install.packages("ggprism")

library("ggprism")

ggplot(gapminder_1997)+
  aes(x=gdpPercap, y=lifeExp)+
  geom_point()+
  facet_grid(rows=vars(continent))

ggsave("awesome_plot.tiff", width=6, height=4)







name <- "Ben"
age <- "26"
name <- "Harry Potter"
name <- "Ben"
name
age <- 26
age
name <- "Harry Potter"
name
read_csv()
?read.csv()
Sys.Date()
getwd()
round(3.1415)
round(3.1415,3)
round(x = 3.1415)
round(x = 3.1415, digits = 2)
round(digits = 2, x = 3.1415)
round(2, 3.1415)
