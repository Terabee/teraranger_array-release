^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package teraranger_array
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.2.1 (2017-12-06)
------------------
* Correct wrong euler factor
* Contributors: Pierre-Louis Kabaradjian

1.2.0 (2017-12-05)
------------------
* Clean dynamic reconfigure .cfg files
* Remove unsupported modes
* Add node namespace to every log message
* Remove old debug messages
* Add ack check when sending commands
* Correct rate commands
* Set defaults modes in both dynamic reconfigure and driver init
* Disable custom firing mode
* Remove unnecessary rates
* Contributors: Pierre-Louis Kabaradjian

1.1.0 (2017-11-17)
------------------
* Change license to MIT
* Update link
* Contributors: Pierre-Louis Kabaradjian, Baptiste Potier

1.0.1 (2017-09-20)
------------------
* Update package.xml
* Contributors: Pierre-Louis Kabaradjian

1.0.0 (2017-09-18)
------------------

* Use ros-serial and remove old serial files
* Standardize topic names
* Use REP 117
* Use RangeArray message, append namespace to frame_id
* Send disable cmd when driver exits
* Refactor trone and multiflex drivers
* Initial commit

* Contributors: Pierre-Louis Kabaradjian, Krzysztof Zurad, Mateusz Sadowski, Baptiste Potier
