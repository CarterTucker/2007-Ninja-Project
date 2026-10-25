# 2007 Kawasaki Ninja 250 Project

**Ongoing restoration, engine rebuild, electrical troubleshooting, and digital instrumentation development for a 2007 Kawasaki Ninja 250.**

<p align="center">
  <img src="media/images/complete-bike.jpg" alt="2007 Kawasaki Ninja 250 project motorcycle" width="720">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Project-Ongoing-6B7280?style=flat-square" alt="Project status: ongoing">
  <img src="https://img.shields.io/badge/Mechanical-Engine%20rebuild-6B7280?style=flat-square" alt="Mechanical: engine rebuild">
  <img src="https://img.shields.io/badge/Electronics-Arduino%20Nano-6B7280?style=flat-square" alt="Electronics: Arduino Nano">
  <img src="https://img.shields.io/badge/CAD-Frame%20model-6B7280?style=flat-square" alt="CAD: frame model">
</p>

**Author:** Carter Tucker

## Overview

This project began with a non-running 2007 Kawasaki Ninja 250 acquired for free as a parts bike. The work has grown from troubleshooting the fuel and ignition systems into a top-end engine rebuild, electrical-system repair, preliminary frame CAD, and experiments in digital engine instrumentation.

Completed work includes carburetor troubleshooting and replacement, repair of a damaged wiring harness, ignition troubleshooting, and preliminary optocoupler-based sensing of ignition-coil signals with an Arduino Nano. The engine is currently removed from the motorcycle, with the cylinder head and cylinders separated from the crankcase while the top end is inspected and rebuilt.

## Current status

| Workstream | Status |
|---|---|
| Original carburetor disassembly and ultrasonic cleaning | Complete |
| Replacement carburetor adjusted toward factory specifications | Complete |
| Damaged wiring harness repair | Complete; needs validation through sustained running |
| Temporary ignition-solenoid bypass switch | Used during initial troubleshooting; not intended as the final solution |
| Short-duration engine start | Achieved; engine ran roughly |
| Optocoupler sensing of ignition-coil signals | Preliminary signals observed; RPM measurement not yet validated |
| Engine removal and top-end teardown | In progress |
| Piston and valve cleaning | Started |
| Valve removal, inspection, and lapping | Planned / tools and materials pending |
| Gasket replacement and engine reassembly | Pending |
| Reliable running and post-rebuild testing | Not yet achieved |
| Frame CAD model | In progress |
| Digital instrumentation | Experimental / future development |
| Repaint or powder coating | Planned |

## Project gallery

GitHub renders repository images directly in a README, so a separate gallery website is not required. Add new photos to `media/images/` and update the paths below.

### Motorcycle and overall condition

<p align="center">
  <img src="media/images/complete-bike.jpg" alt="Complete motorcycle" width="48%">
  <img src="media/images/naked-bike.jpg" alt="Motorcycle with bodywork removed" width="48%">
</p>

### Fuel system

<p align="center">
  <img src="media/images/carb-before.jpg" alt="Carburetor before cleaning" width="32%">
  <img src="media/images/carb-cleaned.jpg" alt="Carburetor after cleaning" width="32%">
  <img src="media/images/carb-new.jpg" alt="Replacement carburetor" width="32%">
</p>

### Engine teardown and rebuild


<p align="center">
  <img src="media/images/carb-new.jpg" alt="Replacement carburetor" width="30%">
  <img src="media/images/engine-removal1.JPG" alt="Preparing for engine removal" width="30%">
  <img src="media/images/engine-removal2.JPG" alt="Lowering the engine" width="30%">
</p>

<p align="center">
  <img src="media/images/engine-in-elevator.JPG" alt="Engine transported in dorm elevator" width="30%">
  <img src="media/images/engine-on-desk.JPG" alt="Removed engine on work surface" width="30%">
  <img src="media/images/engine-cylinders-removed.JPG" alt="Engine with cylinders removed" width="30%">
</p>

<p align="center">
  <img src="media/images/engine-cylinders.JPG" alt="Removed engine cylinders" width="30%">
  <img src="media/images/engine-pistons-cleaned.JPG" alt="Cleaned engine pistons" width="30%">
  <img src="media/images/engine-valves.JPG" alt="Engine valves" width="30%">
</p>

<p align="center">
  <img src="media/images/engine-camshaft.JPG" alt="Engine camshaft" width="30%">
  <img src="media/images/engine-cam-caps.JPG" alt="Camshaft caps" width="30%">
  <img src="media/images/engine-rocker-arms.JPG" alt="Engine rocker arms" width="30%">
</p>

<p align="center">
  <img src="media/images/camshaft-chain-tensioner.JPG" alt="Camshaft chain tensioner" width="30%">
  <img src="media/images/engine-timing.JPG" alt="Engine timing components and timing marks" width="30%">
</p>


## Mechanical restoration

### Carburetor diagnosis

The original carburetor was heavily contaminated with green deposits. It was disassembled, ultrasonically cleaned, and rebuilt with adjustments made toward factory specifications, including float height and fuel-mixture settings.

During reassembly, a jet was tightened too far and its tip entered the carburetor body. This was not initially noticed. The issue was later suspected after the engine intake showed no visible fuel wetness. A replacement carburetor was acquired and adjusted toward factory specifications before installation.

The replacement carburetor allowed the engine to run in short bursts, establishing that the fuel-system work had made progress, although the engine still ran roughly and was not reliable.

> **TODO:** Add the carburetor identification, verified service-manual specifications, and final jet, float-height, or mixture settings. Don't label an adjustment factory-correct unless you've confirmed it against the manual.

### Engine teardown

The short running periods and dry spark plugs raised questions about the engine's mechanical condition, including compression, valve sealing, and cam timing. These observations were not sufficient to establish a single root cause, so the engine was removed for inspection.

The current work includes cleaning the pistons and valves. Valve-removal tools, replacement gaskets, and lapping compound are pending. Planned work is to inspect the valve train and sealing surfaces, assess relevant clearances and components, complete the required service work, and reassemble the engine according to the service manual.

| Item | Status / result |
|---|---|
| Compression test before teardown | TODO — state whether performed; no result currently documented |
| Leak-down test | TODO |
| Valve clearances measured | TODO |
| Valve sealing / leakage test | TODO |
| Cylinder and piston measurements | TODO |
| Cam timing verification | TODO |
| Inspection findings and confirmed root cause | TODO |
| Service-manual specifications used | TODO |
| Parts replaced during rebuild | TODO |

The engine's underlying fault is still being diagnosed. Low compression, carbon buildup, valve sealing, and cam timing were considered possibilities; none should be described as the confirmed cause until inspection or measurement supports it.

## Electrical troubleshooting

The motorcycle's wiring was damaged, likely by rodents. The harness was repaired, and the electrical system was brought back to a state where the bike could be started during short troubleshooting runs.

Initially, a switch was installed across the starter solenoid to bypass the normal starting control while diagnosing the system. This was a temporary troubleshooting method, not a finished starting-system design. Document the original fault, repair, and subsequent validation separately.

> **TODO:** Add a before/after wiring photo or diagram. Document which wires or circuits were repaired, what tests were performed, and which original starting and ignition components are now operating normally.

### Ignition-coil signal sensing

An Arduino Nano and optocouplers were used to explore sensing ignition-coil signals while protecting the microcontroller from the higher-voltage ignition environment. Preliminary signals were observed, but the engine would not run for long enough to collect useful data or validate an RPM calculation.

This remains an experiment rather than a completed tachometer. Before relying on the measurement, the signal-conditioning circuit, pulse interpretation, and calculated RPM need to be checked against a known reference over a stable operating range.

> **TODO:** Add the circuit schematic, optocoupler part number, resistor values, Arduino code, sampling/interrupt method, measured waveform, and intended RPM validation method. Verify component values and wiring before presenting the circuit as a final design.

## Digital instrumentation and future development

The longer-term goal is to add digital electronics to the motorcycle. The exact scope is still being developed.

Potential work includes:
- A validated RPM measurement system based on the ignition signal.
- A digital display or data logger for selected engine parameters.
- A documented electrical architecture.
- Further frame CAD and evaluation of potential modifications.

> **TODO:** Define the intended end state: for example, a digital dashboard and logger, additional sensors, or a custom engine-control system. These are materially different projects and should not be presented as equivalent.

## CAD

A preliminary CAD model of the motorcycle frame is in progress. It is currently a basic model and has not yet been documented as a verified, dimensionally accurate representation.

> **TODO:** Add screenshots of the frame model, CAD software, source-file location, measurement/reference method, and which features are modeled accurately versus approximated. If the model is not intended for manufacturing or structural analysis, state that explicitly.

## Development log

Record milestones as the project progresses. Dates and measured results are more useful than a long chronological narrative.

| Date | Milestone | Evidence / notes |
|---|---|---|
| TODO | Acquired motorcycle as a parts bike | TODO |
| TODO | Original carburetor cleaned and rebuilt | TODO |
| TODO | Replacement carburetor installed; short-duration running achieved | `media/videos/first-start.mp4` |
| TODO | Temporary solenoid bypass used during troubleshooting | `media/videos/switch-start.mp4` |
| TODO | Wiring repaired and ignition troubleshooting completed | TODO |
| TODO | Ignition-coil signals observed through optocouplers | TODO |
| TODO | Engine removed and top end disassembled | TODO |
| TODO | Engine rebuild completed | Pending |
| TODO | Stable running and instrumentation validation | Pending |

## Videos

- [First start — rough running](media/videos/first-start.mp4)
- [Temporary fuel-container setup](media/videos/gas-setup.mp4)
- [Temporary starter-solenoid switch](media/videos/switch-start.mp4)

The videos document early troubleshooting, not final operating condition. The first-start clip shows short-duration, rough running; it should not be interpreted as evidence that the engine is currently reliable or that the rebuild is complete.

## Reproducing the work

This is a physical restoration and instrumentation project, so reproduction requires the motorcycle, service documentation, mechanical tools, and test equipment. The repository should collect the supporting documentation as it becomes available.

| Resource | Location / status |
|---|---|
| Kawasaki service manual | `docs/` — TODO: add manual and confirm redistribution is permitted |
| Wiring diagram | TODO |
| Carburetor specifications | TODO |
| Engine inspection measurements | TODO |
| CAD source files | TODO |
| Arduino sketch and circuit diagram | TODO |
| Signal captures / RPM test data | TODO |
| Parts list and replacement part numbers | TODO |

Recommended documentation practices:

1. Record measurements before adjusting or replacing parts.
2. Record the service-manual specification and measured value side by side.
3. Keep photos organized by subsystem and stage, using descriptive filenames.
4. Save raw measurements and test conditions alongside processed results.
5. Separate confirmed diagnoses from hypotheses.
6. Document safety-critical checks before returning the motorcycle to service.

## Limitations and current unknowns

- The engine has not yet completed its rebuild.
- The cause of the original poor running has not been confirmed by documented measurements.
- The short-duration running videos do not establish reliable engine operation.
- The ignition-coil sensing experiment has not yet produced a validated RPM measurement.
- The frame CAD model is preliminary and its dimensional accuracy has not been verified.
- No sustained post-rebuild test data, performance measurements, or validated instrumentation results are currently documented.

## Next milestones

1. Finish engine inspection and measure components against the service manual.
2. Complete valve work, replace required gaskets, and reassemble the engine.
3. Verify cam timing, valve clearances, fluid levels, and other required checks before starting.
4. Start the engine and systematically diagnose any remaining issues.
5. Validate the ignition-signal RPM measurement against a trusted reference.
6. Publish the circuit, code, measurements, and limitations.
7. Improve the frame CAD model and document its purpose and accuracy.
8. Document cosmetic work such as repainting or powder coating if it proceeds.

## Why I started this project

## What I learned

## Acknowledgments

## License

## Contact

Carter Tucker · [LinkedIn](https://www.linkedin.com/in/carter-tucker-36083b32a/)
