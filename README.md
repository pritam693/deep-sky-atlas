# Deep Sky Atlas

A universe simulator in a single web page. It has three modes.

**Atlas.** A free-camera 3D map of real objects in space: exoplanet systems, black holes, pulsars, nebulae, star clusters and galaxies, each at its true sky position and distance.
- Drag to orbit, scroll or pinch to zoom. Scrolling over an object zooms into it.
- Close up, stars, planets, black holes, pulsars and nebulae render in real-time 3D (WebGL).
- **Time machine:** run time from 1 second to 1 billion years per second, forwards or backwards. Planets orbit at their real periods, the Milky Way rotates, nearby stars drift, and Andromeda collides with the Milky Way.
- **Star life cycles:** every catalogued star ages according to its mass. The Sun becomes a red giant and then a white dwarf, Betelgeuse explodes as a supernova, and planets get swallowed by swelling stars.

**Gravity sandbox.** A real N-body simulation. Place or throw stars, planets, neutron stars and black holes, and watch orbits, collisions, mergers and tidal disruptions. Scenes include the Solar System, a circumbinary planet, the chaotic Pythagorean three-body problem, the figure-eight orbit, a black hole shredding a star, and a galaxy collision.

**Cosmic history.** From the Big Bang to 100 billion years from now, using the standard ΛCDM model (H₀ = 67.7, Ωm = 0.31, ΩΛ = 0.69): the glowing plasma, recombination, the dark ages, the first stars, and galaxies forming along the cosmic web.

The whole site is one file, `index.html`, with no build step. It works on any static host, such as Netlify or GitHub Pages.

Some things are simplified: exoplanet sizes are estimates, surfaces are generated rather than real maps, stellar evolution uses simple mass-based models, and the Andromeda merger shows one likely outcome rather than a certainty.
