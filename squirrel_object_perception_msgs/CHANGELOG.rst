^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package squirrel_object_perception_msgs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.8 (2016-02-04)
------------------
* forgot the CMakelists file
* added scene object
* Contributors: mzillich

0.0.7 (2016-02-02)
------------------
* fixed recognition
* Contributors: mzillich

0.0.6 (2016-02-01)
------------------

0.0.4 (2016-01-13)
------------------
* small change in CMakeLists
* added srv and msgs for finding dynamic objects
* include folder not found
* Contributors: ipa-nhg

0.0.3 (2016-01-13)
------------------

0.0.2 (2016-01-13)
------------------
* cleanup of CMakeLists.txt and package.xml. Make sure dependencies are in there as well.
* Contributors: Markus Bajones

0.0.1 (2015-12-16)
------------------
* Moved message and service definitions from squirrel_perception/squirrel_active_exploration to squirrel_common/squirrel_object_perception_msgs. Modified CMakeLists and package.xml to correctly generate the header files.
* Add response in *ObjectTracking.srv
* added attention services
* fixed comments
* Added extra field (pose) to Classification.msg in object_perception_msgs. Needed for active_exploration module.
* demo review 2015
* added object tracking
* now uses pose stammped .. again!
* added service to create objects from segmented clusters
  removed obsolete ObjectRecognizer service (now Recognize
* add services for object DB handling
* Update LookForObject action for planning
* Update LookForObject action
* Add missing srv for object recognizer
* Added missing build dependecy
* srv file changes to return array of array
* added explanations to services
* changed service messages
* added new service message for visualization
* added new service messages
* added new service
* Merge branch 'hydro_dev' of https://github.com/epotapova/common into hydro_dev
  Conflicts:
  squirrel_object_perception_msgs/CMakeLists.txt
  squirrel_object_perception_msgs/package.xml
* added new dependencies
* Fixed naming of services. Added missing dependcies
* Merge pull request `#5 <https://github.com/squirrel-project/squirrel_common/issues/5>`_ from epotapova/hydro_dev
  renamed service
* added new srv
* remove unused srv
* changed compilation
* Merge branch 'hydro_dev' of github.com:mzillich/common into hydro_dev
  Conflicts:
  squirrel_object_perception_msgs/CMakeLists.txt
* added missing action lib dependeny
* added get_saliency.srv compilation
* fix typo in message name
* fix merge conflicts
* first consistent version of interfaces
* first set of messages, services
* Add recognition srv definitions.
* Update CMakeLists.txt
  Use new Action name during catkin_make
* Update and rename Look.action to LookForObject.action
  Old name was too generic.
* enforce squirrel naming convention.
* Contributors: Markus Bajones, Michael Zillich, Tim Patten Desktop, epotapova, ipa-jsf, ipa-robotino, mzillich
