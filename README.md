
# ARMEE Ventilator
Automatic Respiration Management Exclusively for Emergencies

Details and designs for this project are changing rapidly.

Video for overview: https://tinyurl.com/os-vent-vid6

## Communication with team

Join: https://www.helpfulengineering.org/slack
#project-oscillating-ventilator channel

## Designs

* Current preferred design.  See here for files (including solid works): https://github.com/dogcomplex/oscillating_ventilator/tree/0802406738ced803768a7151b4399e3e1ae447ef/army-ventilator/02_Designs/whitney
  * Please read the readme file in that folder^^
* Design doc: https://docs.google.com/document/d/1por1ouQ4hEpHWrM--5hgncuU5_h0UzBLS1P5lqg7H7Q/edit#heading=h.w84bvm9bty9

### Testing request

Team calculated the simplest test should take between 30 to 60 minutes (including set up time) and would be very grateful for the following data:

* Intended Delivered Tidal Volume:  300-500, assess every 100 ml  (simulating patients 50-83 kg, 6 ml/kg )
* Lung Compliance:  10-30, assess every 10 ml/cmH2O
* Airway Resistance: 0-15, assess every 5 cmH2O/l/sec
* Input Pressure (from Source): 50-350, every 75 cmH2O

Recording achieved:  PIP, PEEP, Tidal Volume, Inhale Time, Exhale Time averages over 3 breaths or 10 seconds (feel free to increase time, but not needed)\
Any sequence of these combinations could be aborted when progressing will push past limits of : RR max 30 / min 8,  PIP max 40 / min 10, PEEP max 20 / min 5

Total different max combinations:  3 * 3 * 3 * 5 = 135\
Total time: ~20 seconds * 135 =  45 minutes (plus setup time)

(of course, if you don't mind getting finer grained that would be amazing!)

=====

Bonus from there would be trying different distances between PIP and PEEP, adjusting the calibration screws until PIP - PEEP is 10, 15, 20, 25.  (4 combinations.  89 minutes total)

Finally trying the above for base PEEP of 5, 10, 15, 20  (4 combinations, 6 hours total).  Though this likely have an obvious effect (just increases PIP and PEEP without affecting RR or TV much) in which case - happy to skip entirely!

=====

If that sounds at all reasonable and you have the time to dedicate, please!  Feel free to suggest a better breakdown of tests as well - these are best-guesses, and aimed mainly to inform design rather than certify (though both would be nice).  If there's a proper procedure that covers the same areas faster or better, feel free to use that instead!   And happy to go for even less if you think this is too much or will produce bad data.

Thank you for your consideration and hard work.

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
