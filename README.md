# KLS (Kenpo Learning Simulator)

This repository serves a compilation of the different modules conforming the Kenpo Learning Simulator (KLS). Each component resides on its on container:

 - [kls-mcmarr](https://github.com/AlbertoCasasOrtiz/kls-mcmarr) - Backend of KLS. Follows the mcmarr framework and can be used as a library.
 - [kls-server](https://github.com/AlbertoCasasOrtiz/kls-server) - Django server to run KLS. Uses kls-mcmarr as a library and contains a basic web version of kls and an API that serves as a bridge between the backend and any frontend implementation (e.g., kls-vr).
 - [kls-vr](https://drive.google.com/drive/folders/1-yvBJyNuHu8-HOfopc9Gf8jwLTm6l8Dh?usp=sharing) - A frontend implementation of KLS in virtual reality. It consists on a virtual dojo (martial arts training place) and a virtual instructor that guides the learning of defensive martial arts movements.

# Licenses

All components of KLS are provided under the terms of the <a href="https://www.gnu.org/licenses/agpl-3.0.en.html">GNU Affero General Public License (AGPL) Version 3.0</a> as published by the Free Software Foundation.

All other content, including but not limited to images, text, videos, and any non-software components, is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC-BY-SA-NC)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es).

# Citation

If you use any component of the KLS ecosystem in you project, we kindly ask you to cite our work.
