Our solar system harbours millions of asteroids. On first sight an asteroid
might just be a pile of rock in space. But if you look closer, there's much
more to discover.


# Why do asteroids matter?

Asteroids are the remnant debris of the planet formation processes in the early
solar system. They have affected Earth's evolution in the past and will
continue to do so in the future. Understanding their structure and composition
gives us insights into the solar system's evolutionary history.

Many of them are very rich in minerals. A few companies have already begun to
plan [mining operations on
asteroids](https://en.wikipedia.org/wiki/Asteroid_mining) in near-Earth orbit.
Asteroid mining could have a profound economical impact on both space travel
and life on Earth.

However, asteroids also pose a potential threat for humanity. There is a
remote possibility that a large asteroid will impact Earth. Would an impact
event happen in the present day, the consequence would likely be devastating.
Thus monitoring asteroids is important to be prepared.


# Lack of categorization

Yet only a fraction of asteroids have been successfully categorized. This is
why our team tackled the challenge to study asteroids using machine learning
techniques for the [2015 NASA
SpaceAppsChallenge](https://2015.spaceappschalleng.com).

From space missions and ground-based observations, data about asteroids is
already publicly available. Ascavis brings this data together and makes it
accessible for everyone.


# Data sources

The [Minor Planet Center (MPC)](http://minorplanetcenter.net/) hosts data about
asteroids as a [web service](http://minorplanetcenter.net/web_service) that
give us a broad overview of what asteroids are known and which of their
properties have been determined by scientific research.

Both professional and amateur astronomers contribute valuable observational
data. For instance, researchers can upload raw light curve data to the MPC's
[Asteroid Light Curve Database](http://minorplanetcenter.net/light_curve2/light_curve.php).

We also tapped into the [NASA Infrared Science Archive](https://irsa.ipac.caltech.edu/frontpage/)
to obtain data from space telescopes such as
[Spitzer](https://en.wikipedia.org/wiki/Spitzer_Space_Telescope) and
[WISE](https://en.wikipedia.org/wiki/Wide-field_Infrared_Survey_Explorer).


# Machine learning

Our goal is to eventually use all the aforementioned data to learn more about
those asteroids that have not been classified yet.

First of all, the data has to be normalized into a mathematical form that can
be used as input for the machine learning algorithms. We aim to keep our system
extendable, so that additional data sources can be plugged in as required.
Think about future space missions, newly published data archives or simply
other relevant data sources we have not yet integrated.

(Details about the machine learning process)


# Visualization

In addition to the mere categorization of the data, we wanted to create an
interface to make the heterogeneous data set accessible in a uniform way. The
idea is on one hand to support scientists with our generated data and on the
other to provide a tool for amateurs that opens up the field of asteroid
science for them in an explorative way via visually browsing our web app.


# Conclusion

Ascavis may shed some light on the vast amounts of unclassified objects out
there in interplanetary space and aid our understanding of planet formation,
plans for asteroid mining or the identification of potentially hazardous
asteroids.
