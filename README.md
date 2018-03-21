# My Top 50 on Spotify
by [ddspog](http://ghithub.com/ddspog);

project forked from [ss1993](https://github.com/ss1993/my-spotify-top50) project.

## Introduction

As a part of the Visual Analytics course at UFCG, I have taken my top 50 artists from Spotify using its [API endpoint](https://developer.spotify.com/web-api/get-users-top-artists-and-tracks/) and I made a graph out of it connecting artists that share at least one music genre. Later, I also took advantage of [related artists endpoint](https://developer.spotify.com/web-api/get-related-artists/) to make further connections.

The visualization was made with [d3 v4](https://github.com/d3/d3/wiki) using the [force layout](https://github.com/d3/d3-force).

You can see the demo running [here](https://ddspog.github.io/my-spotify-top50/).

![Example](thumbnail.png)

I took advantage of d3 forceX method to distribute the graph's nodes based on their genre.

The legend was made using the [d3 legend](http://d3-legend.susielu.com) library.

## Updates

- I've made some changes to the CSS and JS file generating the graph to display the genres for each artist;
- I've made collected the data using a Node Jupyter Notebook, that's on this project.
