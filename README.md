
# ARMEE Ventilator
Automatic Respiration Management Exclusively for Emergencies

Details and designs for this project are changing rapidly.

Video for overview: https://tinyurl.com/os-vent-vid6

## Communication with team

Join: https://www.helpfulengineering.org/slack
#project-oscillating-ventilator channel

## Volunteer team distribution

Victoria BC, Canada
West coast, USA
London & Southampton, UK

## Project status

### 2020-04-09 09:00 UTC+0

#### US West coast team

* Have prototypes.
* Some testing performed.
* Trying to solve problem with fine tuning PIP / PEEP at lower pressures: https://helpfulengineering.slack.com/archives/CV56SDD3L/p1586409877098100?thread_ts=1586379305.074100&cid=CV56SDD3L

#### UK volunteers

* Have 3D printed (filament) prototype
* Trying to find academic to help test


## Designs

* Design files (including solid works): https://github.com/dogcomplex/oscillating_ventilator/tree/0802406738ced803768a7151b4399e3e1ae447ef/army-ventilator/02_Designs/whitney
  * Please read the readme file in that folder^^
* Design doc: https://docs.google.com/document/d/1por1ouQ4hEpHWrM--5hgncuU5_h0UzBLS1P5lqg7H7Q/edit#heading=h.w84bvm9bty9

### Specification

*This design in relation to the UK British Chambers of Commerce specification:* https://www.britishchambers.org.uk/media/get/Specification%20For%20RMVS%20Challenge.pdf

* Be reliable for 14 days: ⚠ NOT TESTED
* Provide at least two settings for volume of air/air O2 mix delivered per cycle/breath. These settings to be 450ml +/- 10ml per breath and 350ml +/- 10ml per breath. ⛔ NOT IMPLEMENTED
* Provide this air/air O2 mix at a peak pressure of 350 mm H2O. ⚠ NOT TESTED
* Have the capability for patient supply pipework to remain pressurised at all times to 150mm H20. ⚠ NOT TESTED
* Have an adjustable rate of between 12 and 20 cycles/breaths per minute. ⛔ NOT IMPLEMENTED; trade off between _?_ and _?_
* Deliver at least 400ml of air/air 02 mix in no more than 1.5 seconds. The ability to change the rate at which air is pushed into the patient is desirable but not essential. ⚠ NOT TESTED
* Be built from O2 safe components to avoid the risk of fire and demonstrate avoidance of hot spots. ⚠ NOT TESTED
* Be capable of breathing for an unconscious patient who is unable to breathe for his or herself. Ability to sense when a patient is breathing, and support that breathing is desirable but not es- sential. ⚠ NOT TESTED
* Be able to supply pure air and air O2 mix at a range of concentrations including at least 50% and 100% Oxygen. Oxygen shortages are not expected, but the ability to attach a Commercial Off The Shelf (COTS) portable O2 concentrator machine may be a useful feature. ⛔ NOT IMPLEMENTED
* Support connections for hospital Oxygen supplies – whether driven by piped or cylinder infra- structure. ⛔ NOT IMPLEMENTED
* Be compatible with standard COTS catheter mount fittings (15mm Male 22mm Female). ⛔ NOT IMPLEMENTED
* Fail SAFE, ideally generating a clear alarm on failure. Failure modes to be alarmed include (but are not limited to) pressure loss and O2 loss. ⛔ NOT IMPLEMENTED

This requires $~? and ? hours to construct.

This is not suitable to support more than one patient using a splitter valve.
