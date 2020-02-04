# Fitbit sleep exploring

I am not sharing the raw data for this project since I used data from my own Fitbit archive. However, if you have a Fitbit and want to reproduce similar visuals with your own data, I've got you!

Here's what you need to do to apply this to your own data:

1. export your fitbit archive and download it -- follow steps [here](https://help.fitbit.com/articles/en_US/Help_article/1133)
2. find the sleep files (they should be named `user-site-export/sleep-yyy-mm-dd.json`) and rename them the start of the notebook to match where you've stored your archive

You can then make the following visuals with the `make_graphs.Rmd` code: (1) histogram of hours asleep per day, (2) nightingale plot with bed times and wake-up times, (3) raster plot of sleep by day and time, (4) animated gif of sleep over hours in the day (each dot is a day)

On the code:

- `make_graphs.Rmd` is the R notebook that generates all the contents of `graphs`
- `make_graphs.nb.html` is the rendered notebook

[Here's](https://rpubs.com/apalbright/fitbit-sleep) the link to the notebook on RPubs.
