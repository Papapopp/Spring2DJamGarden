## [4.0.0-alpha.172](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.172) (2022-04-27)


### Bug Fixes

* Enforce rooms to be located at (0,0) ([#576](https://github.com/godot-escoria/escoria-demo-game/issues/576)) ([72e6517](https://github.com/godot-escoria/escoria-demo-game/commit/72e6517a3502872f68ab0f8c2f283a06faefbb83))



## [4.0.0-alpha.171](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.171) (2022-04-24)


### Bug Fixes

* removed calls to inexisting escoria singleton after plugin disbld ([#578](https://github.com/godot-escoria/escoria-demo-game/issues/578)) ([b23adae](https://github.com/godot-escoria/escoria-demo-game/commit/b23adae3604b54d0d1e8851ee3e9022392f79a2e))



## [4.0.0-alpha.170](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.170) (2022-04-23)


### Bug Fixes

* incorrect dialog player type ([3acf5eb](https://github.com/godot-escoria/escoria-demo-game/commit/3acf5ebe2afcb76cdde1357942d53094463d8382))



## [4.0.0-alpha.169](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.169) (2022-04-23)



## [4.0.0-alpha.168](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.168) (2022-04-23)


### Features

* New room 15 files ([#575](https://github.com/godot-escoria/escoria-demo-game/issues/575)) ([488b206](https://github.com/godot-escoria/escoria-demo-game/commit/488b20656deffcfeb3c535ff848035d6a22307e6))



## [4.0.0-alpha.167](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.167) (2022-04-23)


### Features

* Save objects states in Obj Manager to keep them btwn rooms ([#554](https://github.com/godot-escoria/escoria-demo-game/issues/554)) ([4b2b6f5](https://github.com/godot-escoria/escoria-demo-game/commit/4b2b6f516e01e9e84fc99db5aa579d78d6dadc49))



## [4.0.0-alpha.166](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.166) (2022-04-21)



## [4.0.0-alpha.165](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.165) (2022-04-21)


### Bug Fixes

* fixes incorrect date formatting ([#577](https://github.com/godot-escoria/escoria-demo-game/issues/577)) ([c4296a1](https://github.com/godot-escoria/escoria-demo-game/commit/c4296a17a1e498c9905f21f59010522cb378db0e))



## [4.0.0-alpha.164](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.164) (2022-04-21)


### Bug Fixes

* Corrected wether to whether ([584b81a](https://github.com/godot-escoria/escoria-demo-game/commit/584b81a496a95fadb5062dc31ce8db09cc0c3269))



## [4.0.0-alpha.163](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.163) (2022-04-21)


### Code Refactoring

* remove deprecated debug command ([eeea2d0](https://github.com/godot-escoria/escoria-demo-game/commit/eeea2d0e5a83c107fe708143591cc5596347afd0))



## [4.0.0-alpha.162](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.162) (2022-04-19)


### Bug Fixes

* correct change nodes of node type to node2d type to fix transition bug ([1db0bc4](https://github.com/godot-escoria/escoria-demo-game/commit/1db0bc4a3996ff4485c8a1a38f8e27f32e2fcae5))



## [4.0.0-alpha.161](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.161) (2022-04-19)


### Bug Fixes

* change hotspots Node to Node2D to allow for proper room visibility swapping ([b985c42](https://github.com/godot-escoria/escoria-demo-game/commit/b985c42e086395e7becc05f325353d5ca75c42e5))
* fixes issue w/ bottle from room9 and inventory across rooms; fixes issue w/ room10 and text rendering ([9db27c6](https://github.com/godot-escoria/escoria-demo-game/commit/9db27c6a7487b9aab654b6d802f630606906e738))
* missing this parameter ([4b3b96b](https://github.com/godot-escoria/escoria-demo-game/commit/4b3b96b688f46dcbaa186ded94be5d78a51fd373))
* moves game scene removal/addition to room until after transition; still needs testing, especially w instant transitions ([8d1b00b](https://github.com/godot-escoria/escoria-demo-game/commit/8d1b00bb90b31018886275ce8e617778a8d563b9))
* needs instantiation; also small cleanup ([0cf4672](https://github.com/godot-escoria/escoria-demo-game/commit/0cf467216128be9b4c70f1e8271c7e1df7b76fa1))
* prevents async (i.e. events that are yielded to) from overlapping ([3ff3849](https://github.com/godot-escoria/escoria-demo-game/commit/3ff38492323f2cf075a23d6111c1c52002a285ee))
* remove duplicate transition out (needs testing) ([c92c4ed](https://github.com/godot-escoria/escoria-demo-game/commit/c92c4edacf6236695080b7dda646ff2a931ec404))
* should now block for yielding events but only on the same channel ([92e23be](https://github.com/godot-escoria/escoria-demo-game/commit/92e23beb0011c8003ca9c1f6a864e9c9fe3636fb))



## [4.0.0-alpha.160](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.160) (2022-04-19)


### Features

* Added warning message when multiple locations found for an item ([b4a57fa](https://github.com/godot-escoria/escoria-demo-game/commit/b4a57fa7887e843e9f03da319f7589c58d057742))



## [4.0.0-alpha.159](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.159) (2022-04-19)


### Features

* adds in max args checking; also removes duplicate command validation and now properly validates min_args; re-orders validation to allow argument descriptor validation to always be done first; misc. cleanup of error strings ([7050a8a](https://github.com/godot-escoria/escoria-demo-game/commit/7050a8a2fb9b61a4ec5831741e3b57f8dd24094e))


### Bug Fixes

* allows for bare decimals (no leading 0) to be properly interpreted; also adds in additional validation for 'wait' command ([768f65d](https://github.com/godot-escoria/escoria-demo-game/commit/768f65d929ee60ce14a9d94c2cbf585f8137a95c))
* properly validate min_args and remove superfluous validation call to argument descriptor ([157c2f5](https://github.com/godot-escoria/escoria-demo-game/commit/157c2f564c13696c6ae627e5e53e285ac652be69))



## [4.0.0-alpha.158](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.158) (2022-04-09)


### Features

* reports source of ESC errors when possible ([#568](https://github.com/godot-escoria/escoria-demo-game/issues/568)) ([baee79f](https://github.com/godot-escoria/escoria-demo-game/commit/baee79f5a05249d2dcd16111d4243582887b27ee))



## [4.0.0-alpha.157](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.157) (2022-04-08)


### Bug Fixes

* Avoid globals starting with 'i/' ([#556](https://github.com/godot-escoria/escoria-demo-game/issues/556)) ([05f139e](https://github.com/godot-escoria/escoria-demo-game/commit/05f139ef1af50a02182882e8724591d50537260f))



## [4.0.0-alpha.156](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.156) (2022-04-08)


### Features

* adds instant transitions with an object manager rework, along with ([82acf83](https://github.com/godot-escoria/escoria-demo-game/commit/82acf8374d0d4bc16e57d721149ffa6cedd1997f)), closes [#487](https://github.com/godot-escoria/escoria-demo-game/issues/487)


### Bug Fixes

* accommodate empty parameter ([ecb7bfb](https://github.com/godot-escoria/escoria-demo-game/commit/ecb7bfb528d358b2d9a262601fa446b21ff010f6))
* add code to handle scenes run directly from the Godot editor and allow for the current room to be set in the object manager, allowing proper setup ([c87e853](https://github.com/godot-escoria/escoria-demo-game/commit/c87e853ba63e598648cf04e7eeb81152784df601))
* allows for proper reloading of all globals (reserved or otherwise); also now properly saves reserved objects; plus a couple small guards to correct issues while quitting after loading games in certain conditions ([7ff0176](https://github.com/godot-escoria/escoria-demo-game/commit/7ff0176d62a21f6a9450b3a63c23231efd7dc979))
* break loading up into two batches so objects can be loaded and accessed by other code in the loading method here ([2508786](https://github.com/godot-escoria/escoria-demo-game/commit/2508786cdea3337192f1bc6a9349a8f23a0e9ed1))
* eliminates the need to run two batches of ESC commands for loading games by introducing an extra ESC command; also corrects situations where transitions that are mixed and matched don't work together; and additional cleanup ([503d613](https://github.com/godot-escoria/escoria-demo-game/commit/503d6134dd5ba3050287ace1e4d8469e39b5c6d5))
* handles the case where no coroutines are run as part of room creation; also fixes a small bug in ESCCamera ([85b86f3](https://github.com/godot-escoria/escoria-demo-game/commit/85b86f38bebecf949da484ec85b81c1e42ba45a0))
* makes the loading process more consistent by using all ESC commands; also fixes issue caused by loaded save games not executing :setup or :ready, thereby preventing proper room switching in this case ([84c84d3](https://github.com/godot-escoria/escoria-demo-game/commit/84c84d3a0fdf1e8472bdbce873a13e1dceb68520))
* should now also prevent areas from spawning events; also removes a superfluous variable ([6d98e7b](https://github.com/godot-escoria/escoria-demo-game/commit/6d98e7bdce4e9184c5d6af5eb3301e209283c5d5))
* we now need to transition in from :ready in the case of manual transitions ([0556ccb](https://github.com/godot-escoria/escoria-demo-game/commit/0556ccbf322130bc3388da212fa7ef4d93009179))



## [4.0.0-alpha.155](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.155) (2022-04-07)


### Features

* Reverse save games order - issue 211 ([#565](https://github.com/godot-escoria/escoria-demo-game/issues/565)) ([06d37b0](https://github.com/godot-escoria/escoria-demo-game/commit/06d37b0aad28105655098037b8b42ba47489a12a))



## [4.0.0-alpha.154](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.154) (2022-04-05)


### Features

* Added print command to print output at any debug level ([#564](https://github.com/godot-escoria/escoria-demo-game/issues/564)) ([3e80abf](https://github.com/godot-escoria/escoria-demo-game/commit/3e80abf322241677d36da408d7e833c9927a6a5f))



## [4.0.0-alpha.153](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.153) (2022-04-05)


### Features

* Add global interpolation for say command ([#562](https://github.com/godot-escoria/escoria-demo-game/issues/562)) ([167e06b](https://github.com/godot-escoria/escoria-demo-game/commit/167e06bfd55d44636ab61c3aaee115473221cfc5))



## [4.0.0-alpha.152](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.152) (2022-04-05)


### Features

* Added ability to print globals as part of debug messages ([#561](https://github.com/godot-escoria/escoria-demo-game/issues/561)) ([aa6a4c4](https://github.com/godot-escoria/escoria-demo-game/commit/aa6a4c4d50a32ec399e99b4c6ec06fc8940b06fa))



## [4.0.0-alpha.151](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.151) (2022-03-29)


### Bug Fixes

* rand_global fixes ([#555](https://github.com/godot-escoria/escoria-demo-game/issues/555)) ([2c79da1](https://github.com/godot-escoria/escoria-demo-game/commit/2c79da17e4357e63b92580cdff136abde2663896))



## [4.0.0-alpha.150](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.150) (2022-03-29)



## [4.0.0-alpha.149](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.149) (2022-03-26)


### Bug Fixes

* Fix broken camera push. Issue 125 ([9dd06d0](https://github.com/godot-escoria/escoria-demo-game/commit/9dd06d0d81d8bfb0e678c5d5db4e3c5086178c37))



## [4.0.0-alpha.148](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.148) (2022-03-24)


### Features

* intro cutscene ([dd4b120](https://github.com/godot-escoria/escoria-demo-game/commit/dd4b120289d5f32d6a2abfc1ba8ec8000aefe0ea))



## [4.0.0-alpha.147](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.147) (2022-03-24)


### Bug Fixes

* Added animations for the worker character ([3c74e18](https://github.com/godot-escoria/escoria-demo-game/commit/3c74e1811965be899633e32e899eeb90582ed644))



## [4.0.0-alpha.146](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.146) (2022-03-24)


### Bug Fixes

* exit loop as soon as command is found ([#550](https://github.com/godot-escoria/escoria-demo-game/issues/550)) ([38e3eb2](https://github.com/godot-escoria/escoria-demo-game/commit/38e3eb264de8e2480e97e504b108b27566d70002))



## [4.0.0-alpha.145](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.145) (2022-03-23)


### Bug Fixes

* Mirroed ESCItem's talk animation was conflicting with mirrored idle ([284cb0d](https://github.com/godot-escoria/escoria-demo-game/commit/284cb0d53969532f6e9338f8114f75cb927b2f42))



## [4.0.0-alpha.144](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.144) (2022-03-23)


### Bug Fixes

* eliminate escoria/esc/command_paths that duplicates escoria/main/command_directories ([a3c8fe8](https://github.com/godot-escoria/escoria-demo-game/commit/a3c8fe882e75dfd2eee0d04318e87eefc8686778))



## [4.0.0-alpha.143](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.143) (2022-03-21)


### Features

* Updated exit documentation ([#545](https://github.com/godot-escoria/escoria-demo-game/issues/545)) ([23ce44e](https://github.com/godot-escoria/escoria-demo-game/commit/23ce44eefbd234d25e16bea4eccf8b20e49b97cc))



## [4.0.0-alpha.142](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.142) (2022-03-21)


### Bug Fixes

* out of bounds exception in camera_push ([#546](https://github.com/godot-escoria/escoria-demo-game/issues/546)) ([3c0ebf1](https://github.com/godot-escoria/escoria-demo-game/commit/3c0ebf1869d54da521992b838abbd0b6b3c39e6e))



## [4.0.0-alpha.141](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.141) (2022-03-18)



## [4.0.0-alpha.140](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.140) (2022-03-17)


### Bug Fixes

* Reset audio bus layout ([#542](https://github.com/godot-escoria/escoria-demo-game/issues/542)) ([e98209d](https://github.com/godot-escoria/escoria-demo-game/commit/e98209d3877668652565de823028c03697ede8eb))



## [4.0.0-alpha.139](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.139) (2022-03-17)



## [4.0.0-alpha.138](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.138) (2022-03-17)



## [4.0.0-alpha.137](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.137) (2022-03-17)


### Features

* Add walk fast flag to walk_pos commands to make them consistent with the walk commands ([1b4f3dc](https://github.com/godot-escoria/escoria-demo-game/commit/1b4f3dccfe6a68bff69386857add1a33b455995c))



## [4.0.0-alpha.136](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.136) (2022-03-15)


### Bug Fixes

* Ensure escoria#apply_settings only called in game not editor ([#543](https://github.com/godot-escoria/escoria-demo-game/issues/543)) ([26e4e4c](https://github.com/godot-escoria/escoria-demo-game/commit/26e4e4c1a3e5b7765c3c122cdbda8166a6c52558))



## [4.0.0-alpha.135](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.135) (2022-03-14)


### Bug Fixes

* Reduced log to warning if multiple navigation polygons are enabled while in editor ([fdd61de](https://github.com/godot-escoria/escoria-demo-game/commit/fdd61de4d57e7f1bcfde32a396f94dcb7dab8ba6)), closes [godot-escoria/escoria-issues#103](https://github.com/godot-escoria/escoria-issues/issues/103)



## [4.0.0-alpha.133](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.133) (2022-03-14)


### Features

* add gamepad support to escoria-ui-simplemouse ([#518](https://github.com/godot-escoria/escoria-demo-game/issues/518)) ([d636c1d](https://github.com/godot-escoria/escoria-demo-game/commit/d636c1d732012830d519a4e40495fb1c659aa4ad))



## [4.0.0-alpha.132](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.132) (2022-03-10)


### Bug Fixes

* Wrong variable used causing a crash on UI de-registering ([cb538ed](https://github.com/godot-escoria/escoria-demo-game/commit/cb538edb017030f47255835f371d5968abaf4134))



## [4.0.0-alpha.131](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.131) (2022-03-10)


### Bug Fixes

* Fix issue [#166](https://github.com/godot-escoria/escoria-demo-game/issues/166) ([9037e16](https://github.com/godot-escoria/escoria-demo-game/commit/9037e160c2d93d9ac7939180b7a4dcc544d8ad75))



## [4.0.0-alpha.130](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.130) (2022-03-10)



## [4.0.0-alpha.129](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.129) (2022-03-10)


### Bug Fixes

* player_start needed to be where the level description is ([061ff91](https://github.com/godot-escoria/escoria-demo-game/commit/061ff9193c8f3c645797b23d7f86845eaa319469))



## [4.0.0-alpha.128](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.128) (2022-03-09)


### Bug Fixes

* Updated camera x limit to 1280 to match the background graphics ([#535](https://github.com/godot-escoria/escoria-demo-game/issues/535)) ([21ebb01](https://github.com/godot-escoria/escoria-demo-game/commit/21ebb017e6be5db0d803862d491abf9a523feec8))



## [4.0.0-alpha.127](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.127) (2022-03-09)


### Bug Fixes

* room text is readable again ([587b3b3](https://github.com/godot-escoria/escoria-demo-game/commit/587b3b316bd201d3f178d2a46f9997b4b72cbf00))



## [4.0.0-alpha.126](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.126) (2022-03-09)


### Features

* Updated room 9 graphics ([7e3688f](https://github.com/godot-escoria/escoria-demo-game/commit/7e3688fa637e4c399ed40ba8def5531fe33a07e7))



## [4.0.0-alpha.125](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.125) (2022-03-09)


### Features

* New graphics room 12 ([a3d531c](https://github.com/godot-escoria/escoria-demo-game/commit/a3d531c89b4eea41822fb5b9cb8efda7353ac265))



## [4.0.0-alpha.124](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.124) (2022-03-09)


### Bug Fixes

* Automatically remove trailing whitespace when parsing scripts to avoid needing to change all regular expressions separately ([b05be36](https://github.com/godot-escoria/escoria-demo-game/commit/b05be369b2b19b8d34afb0a15bb63373805bac02))



## [4.0.0-alpha.123](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.123) (2022-03-08)


### Features

* New graphics for room 8 ([7a64c77](https://github.com/godot-escoria/escoria-demo-game/commit/7a64c7707fe8e5011d559fe2f71f458cde1a7d2e))



## [4.0.0-alpha.122](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.122) (2022-03-08)


### Features

* introduce escoria-ui-keyboard-9verbs to verify register_custom_input_handler() API ([5a77bd6](https://github.com/godot-escoria/escoria-demo-game/commit/5a77bd6fdc100461dc1eeb351299c0fc89d32b14))
* register_custom_input_handler() API ([14cf132](https://github.com/godot-escoria/escoria-demo-game/commit/14cf1327fe0b6e3c16c0df6628293b6197f66708))



## [4.0.0-alpha.121](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.121) (2022-03-07)


### Code Refactoring

* remove trailing whitespace from all .gd files ([7bf3e9f](https://github.com/godot-escoria/escoria-demo-game/commit/7bf3e9f276f45f142cb8c04efcace14039c58d55))



## [4.0.0-alpha.120](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.120) (2022-03-07)



## [4.0.0-alpha.119](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.119) (2022-03-07)



## [4.0.0-alpha.118](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.118) (2022-03-07)


### Bug Fixes

* New graphics for room 10 ([#529](https://github.com/godot-escoria/escoria-demo-game/issues/529)) ([eea74ff](https://github.com/godot-escoria/escoria-demo-game/commit/eea74ff828ab8720db9f054aab9cf80641f6f083))



## [4.0.0-alpha.117](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.117) (2022-03-07)


### Features

* Made room 5's background more interesting ([#530](https://github.com/godot-escoria/escoria-demo-game/issues/530)) ([b70c52e](https://github.com/godot-escoria/escoria-demo-game/commit/b70c52edda01a80aa9e21d4a7287640ae1ef344e))



## [4.0.0-alpha.116](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.116) (2022-03-04)


### Features

* Graphics update for room 5 ([#525](https://github.com/godot-escoria/escoria-demo-game/issues/525)) ([bcb366c](https://github.com/godot-escoria/escoria-demo-game/commit/bcb366c6af91f1e4e89543844f663b88881c7d32))



## [4.0.0-alpha.115](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.115) (2022-03-03)


### Bug Fixes

* early return for mouse_in_shape ([f21ec15](https://github.com/godot-escoria/escoria-demo-game/commit/f21ec15560d61fa81c858c515aec2db447f5fa40))



## [4.0.0-alpha.114](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.114) (2022-03-03)


### Code Refactoring

* remove redundant check for camera node ([10f7708](https://github.com/godot-escoria/escoria-demo-game/commit/10f770855ffbc6b4880ca80eaf6fc4885a920269))



## [4.0.0-alpha.113](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.113) (2022-03-03)



## [4.0.0-alpha.112](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.112) (2022-03-03)


### Features

* New graphics for room 7 ([75a78f6](https://github.com/godot-escoria/escoria-demo-game/commit/75a78f63e10d1971655bc4e02efa5fc535290cd3))



## [4.0.0-alpha.111](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.111) (2022-03-03)


### Bug Fixes

* parameter validation function cant print arrays ([4fbe352](https://github.com/godot-escoria/escoria-demo-game/commit/4fbe3527e8fc24bd37f349fbfe907ffd68367593))



## [4.0.0-alpha.110](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.110) (2022-03-03)


### Features

* more useful error messages ([5bdd519](https://github.com/godot-escoria/escoria-demo-game/commit/5bdd519d67527b1052fa15495eae8c145c4af1e3))



## [4.0.0-alpha.109](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.109) (2022-03-01)


### Bug Fixes

* ESCItem that is a trigger should not capture input events ([#516](https://github.com/godot-escoria/escoria-demo-game/issues/516)) ([0570edc](https://github.com/godot-escoria/escoria-demo-game/commit/0570edc3ff6c11280ddb616387b5ba01f91665d8))



## [4.0.0-alpha.108](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.108) (2022-02-27)


### Bug Fixes

* add validates to camera commands missing them ([#508](https://github.com/godot-escoria/escoria-demo-game/issues/508)) ([02a66fe](https://github.com/godot-escoria/escoria-demo-game/commit/02a66fecda5a3193ed495d6ef449862b4f375d01))



## [4.0.0-alpha.107](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.107) (2022-02-25)


### Bug Fixes

* fix error message - bug 143 ([#513](https://github.com/godot-escoria/escoria-demo-game/issues/513)) ([deac3df](https://github.com/godot-escoria/escoria-demo-game/commit/deac3df61dee8f60c20ff75437cd508ea77b3aad))



## [4.0.0-alpha.106](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.106) (2022-02-25)


### Bug Fixes

* check to see if requested camera limit is invalid. ([#512](https://github.com/godot-escoria/escoria-demo-game/issues/512)) ([348a2b6](https://github.com/godot-escoria/escoria-demo-game/commit/348a2b697cf400dff8297899f5dde4537bd77e6c))



## [4.0.0-alpha.105](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.105) (2022-02-25)


### Bug Fixes

* stops negative numbers being interpreted as strings ([#511](https://github.com/godot-escoria/escoria-demo-game/issues/511)) ([5adf5b8](https://github.com/godot-escoria/escoria-demo-game/commit/5adf5b8d49a6be43303819bc50cd0e2c320f8e8e))



## [4.0.0-alpha.104](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.104) (2022-02-25)



## [4.0.0-alpha.103](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.103) (2022-02-25)


### Bug Fixes

* camera commands to use time instead of speed ([#509](https://github.com/godot-escoria/escoria-demo-game/issues/509)) ([d3f1b8b](https://github.com/godot-escoria/escoria-demo-game/commit/d3f1b8b6e2757d0c3ecf976bb496395a34af15f2))



## [4.0.0-alpha.102](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.102) (2022-02-24)


### Bug Fixes

* enable transition to ESCRoom even if esc_script is not set ([#502](https://github.com/godot-escoria/escoria-demo-game/issues/502)) ([282ea24](https://github.com/godot-escoria/escoria-demo-game/commit/282ea24b7dbbcc747d0fe256a2fe4aaa3fc59e17))



## [4.0.0-alpha.101](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.101) (2022-02-19)



## [4.0.0-alpha.100](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.100) (2022-02-19)


### Bug Fixes

* animations doesnt have a speaks parameter when it is null ([1664140](https://github.com/godot-escoria/escoria-demo-game/commit/166414098ac265affbe60178559bd745a6217454))



## [4.0.0-alpha.99](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.99) (2022-02-17)


### Code Refactoring

* Whitespace removal from all .gd files ([#494](https://github.com/godot-escoria/escoria-demo-game/issues/494)) ([21df2af](https://github.com/godot-escoria/escoria-demo-game/commit/21df2af2c8848a709352402c2f36af4b16c57c1e))



## [4.0.0-alpha.98](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.98) (2022-02-17)


### Features

* Removed obsolete code. Fixes godot-escoria/escoria-issues[#99](https://github.com/godot-escoria/escoria-demo-game/issues/99) ([#499](https://github.com/godot-escoria/escoria-demo-game/issues/499)) ([b40c0a2](https://github.com/godot-escoria/escoria-demo-game/commit/b40c0a241ca55e65de58184cc43b4e274dc1b388))



## [4.0.0-alpha.97](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.97) (2022-02-17)



## [4.0.0-alpha.96](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.96) (2022-02-17)



## [4.0.0-alpha.95](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.95) (2022-02-16)


### Bug Fixes

* guard for cases where no animations are set. ([ea3543b](https://github.com/godot-escoria/escoria-demo-game/commit/ea3543b5ee612b08d0bc4538184300a69b572e79))
* set a proper guard in case of no speaking animations and correct the upper limit check for the speaking index ([31b5750](https://github.com/godot-escoria/escoria-demo-game/commit/31b57505b59008b0d013251dbbf7b94e9b0cdb89))



## [4.0.0-alpha.94](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.94) (2022-02-15)


### Features

* Debug set state animations ([#495](https://github.com/godot-escoria/escoria-demo-game/issues/495)) ([5e0e83f](https://github.com/godot-escoria/escoria-demo-game/commit/5e0e83f23edf4ef782f1a7773f2e5d1d2594faf3))



## [4.0.0-alpha.93](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.93) (2022-02-15)


### Bug Fixes

* use Escoria plugin version from plugin.cfg in savegames ([#489](https://github.com/godot-escoria/escoria-demo-game/issues/489)) ([2384127](https://github.com/godot-escoria/escoria-demo-game/commit/2384127ca4aa7c262d2944885af615c492cab002))



## [4.0.0-alpha.92](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.92) (2022-02-12)


### Features

* Updated room 1 graphics ([#491](https://github.com/godot-escoria/escoria-demo-game/issues/491)) ([5005267](https://github.com/godot-escoria/escoria-demo-game/commit/5005267e0dba684b6e4036023bd344a60e3ccccd))



## [4.0.0-alpha.91](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.91) (2022-02-06)


### Bug Fixes

* set a proper guard in case of no speaking animations ([#488](https://github.com/godot-escoria/escoria-demo-game/issues/488)) ([326618d](https://github.com/godot-escoria/escoria-demo-game/commit/326618df180a72f700f9917e1139f246abae918e))



## [4.0.0-alpha.90](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.90) (2022-02-04)


### Features

* refactor numerous areas and tokenize string literals where possible; also fixes some small bugs ([#487](https://github.com/godot-escoria/escoria-demo-game/issues/487)) ([99dc1e0](https://github.com/godot-escoria/escoria-demo-game/commit/99dc1e01106ce651d1b78ae574cca9d0202c48b1))



## [4.0.0-alpha.89](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.89) (2022-02-04)



## [4.0.0-alpha.88](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.88) (2022-01-17)



## [4.0.0-alpha.87](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.87) (2022-01-13)



## [4.0.0-alpha.86](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.86) (2021-12-31)



## [4.0.0-alpha.85](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.85) (2021-12-15)



## [4.0.0-alpha.84](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.84) (2021-12-14)



## [4.0.0-alpha.83](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.83) (2021-12-13)



## [4.0.0-alpha.82](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.82) (2021-12-13)


### Features

* move room initialization code into manager ([#479](https://github.com/godot-escoria/escoria-demo-game/issues/479)) ([e9d63e9](https://github.com/godot-escoria/escoria-demo-game/commit/e9d63e94b0f69146224eecf33dbb61124db45ff6))



## [4.0.0-alpha.81](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.81) (2021-12-06)


### Bug Fixes

* Support Godot 3.4 ([#478](https://github.com/godot-escoria/escoria-demo-game/issues/478)) ([84adc0a](https://github.com/godot-escoria/escoria-demo-game/commit/84adc0ac9b03f344565a1dbd2f78824b62ba9205))



## [4.0.0-alpha.80](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.80) (2021-12-06)


### Features

* add options menu to pause menu ([#477](https://github.com/godot-escoria/escoria-demo-game/issues/477)) ([fd47499](https://github.com/godot-escoria/escoria-demo-game/commit/fd47499fed9c1db335c9d06e3aefbca240a15fff))



## [4.0.0-alpha.79](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.79) (2021-12-03)


### Bug Fixes

* correct data type and update missed constant references ([#476](https://github.com/godot-escoria/escoria-demo-game/issues/476)) ([9fbf0c2](https://github.com/godot-escoria/escoria-demo-game/commit/9fbf0c254c9790f0c8de6fc91f2dda18b72afb7f))



## [4.0.0-alpha.78](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.78) (2021-12-03)


### Features

* add esc_current_scene reserved global ([#474](https://github.com/godot-escoria/escoria-demo-game/issues/474)) ([391bf08](https://github.com/godot-escoria/escoria-demo-game/commit/391bf08f217aa2248f7172be1449b436d7b88966))



## [4.0.0-alpha.77](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.77) (2021-12-01)


### Features

* Support for Escoria and Game migrations ([#473](https://github.com/godot-escoria/escoria-demo-game/issues/473)) ([b5d5217](https://github.com/godot-escoria/escoria-demo-game/commit/b5d5217aa4971769e9ff775e3b151c48fc8f286e))



## [4.0.0-alpha.76](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.76) (2021-12-01)



## [4.0.0-alpha.75](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.75) (2021-12-01)


### Bug Fixes

* makes dialog players pausable by removing yields ([#472](https://github.com/godot-escoria/escoria-demo-game/issues/472)) ([b4d5e38](https://github.com/godot-escoria/escoria-demo-game/commit/b4d5e380e6072745688cc9420cedd553b87bc3ff))



## [4.0.0-alpha.74](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.74) (2021-11-29)



## [4.0.0-alpha.73](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.73) (2021-11-29)



## [4.0.0-alpha.72](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.72) (2021-11-28)


### Bug Fixes

* Safety guards for disconnects ([#470](https://github.com/godot-escoria/escoria-demo-game/issues/470)) ([14887c7](https://github.com/godot-escoria/escoria-demo-game/commit/14887c711bb09da14057624e39444898323125bd))



## [4.0.0-alpha.71](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.71) (2021-11-28)


### Features

* Support WAV files as well ([#469](https://github.com/godot-escoria/escoria-demo-game/issues/469)) ([0e295f0](https://github.com/godot-escoria/escoria-demo-game/commit/0e295f0ebbd411d4a4946f9b96d76c3524dd983f))



## [4.0.0-alpha.70](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.70) (2021-11-28)


### Bug Fixes

* Fixes from the ETF release day ([#468](https://github.com/godot-escoria/escoria-demo-game/issues/468)) ([84fe9b6](https://github.com/godot-escoria/escoria-demo-game/commit/84fe9b64afe92d20ba7e937f45b6a69553f7b1c9))



## [4.0.0-alpha.69](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.69) (2021-11-27)


### Features

* Several fixes and optimizations ([#467](https://github.com/godot-escoria/escoria-demo-game/issues/467)) ([47fe4df](https://github.com/godot-escoria/escoria-demo-game/commit/47fe4df8419974b8e7469b76670728e658bd1a04))



## [4.0.0-alpha.68](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.68) (2021-11-26)


### Bug Fixes

* Fixes smaller things ([#465](https://github.com/godot-escoria/escoria-demo-game/issues/465)) ([8c9ee73](https://github.com/godot-escoria/escoria-demo-game/commit/8c9ee734fdc89867635e5605448c6e99db68550d))



## [4.0.0-alpha.67](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.67) (2021-11-25)



## [4.0.0-alpha.66](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.66) (2021-11-25)


### Features

* Optimized animation handler and crashing ([#463](https://github.com/godot-escoria/escoria-demo-game/issues/463)) ([75c00b4](https://github.com/godot-escoria/escoria-demo-game/commit/75c00b4993aa59e7962fd50f085d12c660174945))



## [4.0.0-alpha.65](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.65) (2021-11-25)



## [4.0.0-alpha.64](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.64) (2021-11-25)


### Features

* Fix set_interactive command ([#461](https://github.com/godot-escoria/escoria-demo-game/issues/461)) ([87ef970](https://github.com/godot-escoria/escoria-demo-game/commit/87ef9708dedb7ded655efee3286bade95b54bc30))



## [4.0.0-alpha.63](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.63) (2021-11-23)



## [4.0.0-alpha.62](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.62) (2021-11-23)


### Features

* Keep current animations resource ([#459](https://github.com/godot-escoria/escoria-demo-game/issues/459)) ([7963f03](https://github.com/godot-escoria/escoria-demo-game/commit/7963f03087be6f8832a5aad231dc2834c5237256))



## [4.0.0-alpha.61](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.61) (2021-11-23)


### Bug Fixes

* Fixes signal handling on AnimationPlayer nodes. ([#458](https://github.com/godot-escoria/escoria-demo-game/issues/458)) ([860c6ad](https://github.com/godot-escoria/escoria-demo-game/commit/860c6adc207bfbc80877dac731005d351e93824b))



## [4.0.0-alpha.60](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.60) (2021-11-22)


### Bug Fixes

* Safety guard for characters without speaking animations ([#457](https://github.com/godot-escoria/escoria-demo-game/issues/457)) ([f4c5803](https://github.com/godot-escoria/escoria-demo-game/commit/f4c5803646f41375b77dd153fc2711ede92f4592))



## [4.0.0-alpha.59](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.59) (2021-11-22)



## [4.0.0-alpha.58](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.58) (2021-11-22)


### Features

* New streamlined exit item ([#455](https://github.com/godot-escoria/escoria-demo-game/issues/455)) ([e14373b](https://github.com/godot-escoria/escoria-demo-game/commit/e14373b1790830f45621c8ec7ca99ed0b50b6d68))



## [4.0.0-alpha.57](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.57) (2021-11-22)


### Features

* This introduces background events queue in Escoria ([#444](https://github.com/godot-escoria/escoria-demo-game/issues/444)) ([9adc7bb](https://github.com/godot-escoria/escoria-demo-game/commit/9adc7bbadeaf2788a445659b774862aadd167843))



## [4.0.0-alpha.56](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.56) (2021-11-21)



## [4.0.0-alpha.55](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.55) (2021-11-21)



## [4.0.0-alpha.54](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.54) (2021-11-21)


### Bug Fixes

* Optimized ESC command docs ([#450](https://github.com/godot-escoria/escoria-demo-game/issues/450)) ([012d978](https://github.com/godot-escoria/escoria-demo-game/commit/012d978d668b8f5322d16532220a4e014176361c))



## [4.0.0-alpha.53](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.53) (2021-11-21)


### Bug Fixes

* Say command fixes ([#452](https://github.com/godot-escoria/escoria-demo-game/issues/452)) ([dbc7415](https://github.com/godot-escoria/escoria-demo-game/commit/dbc7415aaf66df415e3f9c2461db30debade0011))



## [4.0.0-alpha.52](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.52) (2021-11-18)



## [4.0.0-alpha.51](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.51) (2021-11-18)



## [4.0.0-alpha.50](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.50) (2021-11-18)



## [4.0.0-alpha.49](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.49) (2021-11-18)



## [4.0.0-alpha.48](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.48) (2021-11-18)


### Features

* Optimizes animation commands ([#446](https://github.com/godot-escoria/escoria-demo-game/issues/446)) ([c9a6f80](https://github.com/godot-escoria/escoria-demo-game/commit/c9a6f802c7a7a1f009bd90731fba31e3cfa09938))



## [4.0.0-alpha.47](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.47) (2021-11-17)



## [4.0.0-alpha.46](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.46) (2021-11-15)


### Bug Fixes

* Resets the current verb after the action has finished ([#443](https://github.com/godot-escoria/escoria-demo-game/issues/443)) ([9068bb8](https://github.com/godot-escoria/escoria-demo-game/commit/9068bb8e94c423e69596e11b01ab1e6bee2124d4))



## [4.0.0-alpha.45](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.45) (2021-11-15)


### Bug Fixes

* Fixed more input events ([#442](https://github.com/godot-escoria/escoria-demo-game/issues/442)) ([b626973](https://github.com/godot-escoria/escoria-demo-game/commit/b626973f117420da25bd0af361776c0cc86d4947))



## [4.0.0-alpha.44](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.44) (2021-11-15)



## [4.0.0-alpha.43](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.43) (2021-11-14)



## [4.0.0-alpha.42](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.42) (2021-11-14)


### Bug Fixes

* Fixed input problems ([#440](https://github.com/godot-escoria/escoria-demo-game/issues/440)) ([c4d1432](https://github.com/godot-escoria/escoria-demo-game/commit/c4d1432d66b32245638f5f211487a087abd71507))



## [4.0.0-alpha.41](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.41) (2021-11-13)



## [4.0.0-alpha.40](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.40) (2021-11-13)



## [4.0.0-alpha.39](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.39) (2021-11-12)



## [4.0.0-alpha.38](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.38) (2021-11-12)



## [4.0.0-alpha.37](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.37) (2021-11-12)



## [4.0.0-alpha.36](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.36) (2021-11-12)



## [4.0.0-alpha.35](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.35) (2021-11-12)


### Bug Fixes

* Fixed apidoc workflow to comply with latest doc changes ([bf8929b](https://github.com/godot-escoria/escoria-demo-game/commit/bf8929ba2d4be5165e0d463eb72cef2f97576475))



## [4.0.0-alpha.34](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.34) (2021-11-12)


### Features

* Optimized ESCCamera ([#434](https://github.com/godot-escoria/escoria-demo-game/issues/434)) ([15b3e30](https://github.com/godot-escoria/escoria-demo-game/commit/15b3e30e28e977fc62922e33d543b848bb513e15))



## [4.0.0-alpha.33](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.33) (2021-11-11)



## [4.0.0-alpha.32](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.32) (2021-11-11)



## [4.0.0-alpha.31](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.31) (2021-11-11)



## [4.0.0-alpha.30](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.30) (2021-11-11)


### Bug Fixes

* Make float dialog follow character ([#430](https://github.com/godot-escoria/escoria-demo-game/issues/430)) ([b908a2a](https://github.com/godot-escoria/escoria-demo-game/commit/b908a2aeeed62d2d1e96e29e0b1c904e51097cd1))



## [4.0.0-alpha.29](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.29) (2021-11-07)


### Bug Fixes

* Fixes skipping empty or comment lines in groups and dialogs ([#429](https://github.com/godot-escoria/escoria-demo-game/issues/429)) ([8b70448](https://github.com/godot-escoria/escoria-demo-game/commit/8b70448bf7feea2387d4b82aa23e9b7ca9f73717))



## [4.0.0-alpha.28](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.28) (2021-11-02)


### Bug Fixes

* Don't delete index file in the api directory ([8f378d4](https://github.com/godot-escoria/escoria-demo-game/commit/8f378d40e89082cdcab950a86c725d3baf078f65))



## [4.0.0-alpha.27](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.27) (2021-11-02)


### Bug Fixes

* Corrected variable name ([#428](https://github.com/godot-escoria/escoria-demo-game/issues/428)) ([d42c973](https://github.com/godot-escoria/escoria-demo-game/commit/d42c9733691cd89ce3ad75f20ce66b7254c69625))



## [4.0.0-alpha.26](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.26) (2021-11-02)


### Documentation

* Fixed doc generation ([092df6c](https://github.com/godot-escoria/escoria-demo-game/commit/092df6c7eee67f849c76935537a66d62cb74f0f0))



## [4.0.0-alpha.25](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.25) (2021-11-02)


### Documentation

* Fixed doc generation ([c986b64](https://github.com/godot-escoria/escoria-demo-game/commit/c986b64a9e6606ca5c67e8639c86c25f165d4296))



## [4.0.0-alpha.24](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.24) (2021-11-02)


### Documentation

* Reorganized docs to the docs repo ([#426](https://github.com/godot-escoria/escoria-demo-game/issues/426)) ([94f77cf](https://github.com/godot-escoria/escoria-demo-game/commit/94f77cf6463717c18d294e6ddce4747898640e4b))



## [4.0.0-alpha.23](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.23) (2021-11-01)



## [4.0.0-alpha.22](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.22) (2021-11-01)



## [4.0.0-alpha.21](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.21) (2021-10-27)



## [4.0.0-alpha.20](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.20) (2021-10-27)



## [4.0.0-alpha.19](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.19) (2021-10-27)



## [4.0.0-alpha.18](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.18) (2021-10-27)



## [4.0.0-alpha.17](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.17) (2021-10-27)



## [4.0.0-alpha.16](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.16) (2021-10-27)



## [4.0.0-alpha.15](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.15) (2021-10-27)


### Documentation

* Automatic update of API docs ([08645e6](https://github.com/godot-escoria/escoria-demo-game/commit/08645e6903082b7f943903aa10f6827d8857b230))



## [4.0.0-alpha.14](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.14) (2021-10-27)


### Features

* Made dialogs pluggable ([#424](https://github.com/godot-escoria/escoria-demo-game/issues/424)) ([57ce7fb](https://github.com/godot-escoria/escoria-demo-game/commit/57ce7fbcaeb5693f49c4bc7ee3950ff71be1424c))



## [4.0.0-alpha.13](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.13) (2021-10-26)



## [4.0.0-alpha.12](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.12) (2021-10-26)


### Documentation

* Automatic update of API docs ([5240cce](https://github.com/godot-escoria/escoria-demo-game/commit/5240ccec54421aba3f123fca40c514f076b2bdcc))



## [4.0.0-alpha.11](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.11) (2021-10-26)



## [4.0.0-alpha.10](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.10) (2021-10-25)


### Documentation

* Automatic update of API docs ([ee03321](https://github.com/godot-escoria/escoria-demo-game/commit/ee03321b37ee3e18239dfeaa8ffd4af508210f2e))



## [4.0.0-alpha.9](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.9) (2021-10-25)


### Bug Fixes

* Huge cleanup ([#420](https://github.com/godot-escoria/escoria-demo-game/issues/420)) ([94d86d2](https://github.com/godot-escoria/escoria-demo-game/commit/94d86d24d54197566c1820012634ba95cddb425a))



## [4.0.0-alpha.8](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.8) (2021-10-22)



## [4.0.0-alpha.7](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.7) (2021-10-22)



## [4.0.0-alpha.6](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.6) (2021-10-21)


### Documentation

* Automatic update of API docs ([b04df15](https://github.com/godot-escoria/escoria-demo-game/commit/b04df1506009de4bc061c67fb770d233d261c1a8))



## [4.0.0-alpha.5](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.5) (2021-10-21)


### Features

* Rewrote inventory handling basing on ESCItems ([#417](https://github.com/godot-escoria/escoria-demo-game/issues/417)) ([af26521](https://github.com/godot-escoria/escoria-demo-game/commit/af26521d3da603d81641eed0d9d03ff72d298460))



## [4.0.0-alpha.4](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.4) (2021-10-19)


### Bug Fixes

* Fixed assetlib id ([f0ca51c](https://github.com/godot-escoria/escoria-demo-game/commit/f0ca51c2024b0f0d2be51b328cd19a8c71930e80))



## [4.0.0-alpha.3](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.3) (2021-10-19)



## [4.0.0-alpha.2](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.2) (2021-10-17)



## [4.0.0-alpha.1](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.1) (2021-10-17)


### Bug Fixes

* Fixed prerelease workflow ([cdf0124](https://github.com/godot-escoria/escoria-demo-game/commit/cdf012439351c1fa1470f34015d7f3ab7972dcca))
* Updated attributes and corrected license file typo ([cb67c78](https://github.com/godot-escoria/escoria-demo-game/commit/cb67c780a3d29d9508851e37a69999c7747524b2))



### [4.0.1-alpha.0](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.1-alpha.0) (2021-10-17)


### Bug Fixes

* Updated attributes and corrected license file typo ([cb67c78](https://github.com/godot-escoria/escoria-demo-game/commit/cb67c780a3d29d9508851e37a69999c7747524b2))



## [4.0.0-alpha.0](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.0) (2021-10-16)



## [4.0.0-alpha.0](https://github.com/godot-escoria/escoria-demo-game/compare/v0.0.0...v4.0.0-alpha.0) (2021-10-16)
