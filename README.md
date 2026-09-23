# SM42 for Derail Valley

A community-made SM42 locomotive for [Derail Valley](https://store.steampowered.com/app/588030/Derail_Valley/),
created using Custom Car Loader (CCL).

> ⚠️ Development is currently on hold.
>
> The project is in a playable but unfinished state. I may return to
> development in the future, but for now the repository is available
> for anyone interested in testing, learning from it, or continuing
> development.

## About

This project aims to recreate the Polish SM42 diesel locomotive in
Derail Valley.

The project started as a learning project while I was learning
Blender, Unity and Custom Car Loader. Over time it evolved into a
fairly functional locomotive with its own 3D model, textures,
physics and interactive systems.

## Current state

### Implemented

- Custom SM42 3D model
- Custom exterior texture
- Basic weathering and dirt
- Custom locomotive physics
- Tuned traction characteristics
- Engine power curve
- Engine idle and maximum RPM
- Three stages of field weakening
- Headlights
- Horn
- Sanding system
- Windshield glass
- Rain droplets on windows
- Windshield wipers
- Interactive cab controls
- Basic locomotive operation
- Cargo and shunting testing

### Known issues / unfinished

- Some parts of the 3D model still need refinement
- Some textures are unfinished
- Windshield wipers require further tuning
- Some cab instruments still need proper textures and/or animation
- Brake behaviour may require further balancing
- Sound system is not finished
- Some controls do not yet perfectly reproduce the real SM42 controls
- The project has not received a final gameplay/balance pass

## Performance / physics

The locomotive was intentionally balanced for gameplay rather than
being a perfectly accurate simulation.

Approximate tested hauling capability:

| Conditions | Approx. load |
|------------|--------------|
| Level track | ~2000 t |
| 2% gradient | ~650 t |
| 2% gradient + wet rail | ~550 t |

The engine power curve ends at approximately 588 kW (800 HP), matching
the rated power of the real engine.

## Development

The project was developed primarily as a learning project.

Tools used include:

- Blender
- Unity
- Custom Car Loader (CCL)
- Inkscape / image editing tools

The project also makes use of CCL-provided systems and components.

## Contributing

The project is currently on hold, but contributions and continued
development are welcome.

If you want to experiment with the locomotive, fix bugs, improve the
model, add sounds or continue development, feel free to fork the
repository.

If you make significant changes, feel free to open a pull request.

## License

Original work in this repository is licensed under the MIT License.

This license applies only to original work created for this project.
Third-party software, frameworks, assets and other materials remain
under their respective licenses.

This project uses Custom Car Loader (CCL) for Derail Valley.
CCL is not part of this license.

Derail Valley and its assets are property of their respective
rights holders.

## Third-party content

This project depends on and/or interacts with third-party software
and content, including:

- Derail Valley — Altfuture
- Custom Car Loader (CCL)
- Unity
- Blender

These materials are not relicensed by this repository and remain
subject to their respective licenses and terms.

## Credits

- Custom Car Loader (CCL) — locomotive modding framework
- Derail Valley — original game by Altfuture
- SM42 — original locomotive design by Fablok / Polish State Railways
  and subsequent operators

This project is an unofficial fan-made modification and is not
affiliated with Altfuture.
