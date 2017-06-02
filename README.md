# 42-C-Raytracing

This prgm use the technique of raytracing. I use vectors to solve differents equations in order to draw : sphere, cone, cylinder, plane. (ligths, shadow, filter, effects and animations etc...). 
This programm create an image according to their mathematics formula. Thus, you can create different forms : sphere, cylinder, cone and plane. Multi various bonus was necessary to have good results.
This infography technology is used in diffents cinema animations studios.

# Environment 
Mac os x el capitan

install GTK(librairy for menu)
if any problem to brew:
rm -rf ~/.brew

export HOMEBREW_CACHE=/tmp/mycache

export HOMEBREW_TEMP=/tmp/mytemp

mkdir /tmp/mycache /tmp/mytemp

/usr/local/bin/brew update

~/.brew/bin/brew install …
install gsl(mathematic librairy to solve 4-6 degre equations)

C langage

team project of 4 members (gantt diagramm to share tasks)

# Run
brew gtk
brew gsl
git clone https://github.com/rim31/42_C_raytracing.git
cd 42-C-raytracing
make

./rt scenes/sujet1.rt

(choose a scenes in the folder scenes)

# basic render :
multi ligths
brigthness
Esc to quit the prgm
sphere
plane
cylinder
cone

![Texte alternatif](https://github.com/rim31/42_C_raytracing/blob/master/Screen%20Shot%202016-06-12%20at%206.38.05%20PM.png "homer")

# Bonus :
reflection, exotiques forms : ellipsoide, parabolloide, torrus, triangle, quadrilatere, limited forms, texture, loading info
multi threads, various lights, editor scenes : set up yourself camera , lights, rotation and obejct

![Texte alternatif](https://github.com/rim31/42_C_raytracing/blob/master/Screen%20Shot%202016-06-12%20at%206.16.19%20PM.png "bonus")

# Ultimate bonus:
GTK menu : anti-aliasing, filter speia or various colors, save picture, open scenes in menu
textures, homer, starfox, minion, a pokemon, solar system etc...
![Texte alternatif](https://github.com/rim31/42_C_raytracing/blob/master/Screen%20Shot%202016-06-15%20at%2010.55.48%20AM.png "basic")

Aninamtion : presse E key

# Difficulties: 
Initially, we wated to create a kind of softawre. Thus, i wanted to creat animation movie.
Unforntunally, the code isn't really well optimized. Indeed, using GPU goes as fast as multi thread (8 cores).
Moreover, i tried to code myself a calculator solving equation of 4 degres or more (using Ferrari method or Descart etc...) but it is also too slow.
I had plenty of ideas or imagination making fun scene, like Homer, Bomberman or Starfox. It took 7 weeks.
