.. ET:Legacy assets documentation master file, created by
   sphinx-quickstart on Tue Apr  3 12:40:19 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

===================
Asset Documentation
===================

--------
Foreword
--------

Welcome to ET: Legacy's Asset Documentation!

The original assets included in pak0, pak1 and pak2 unfortunately weren't included in the `source release <https://github.com/id-Software/Enemy-Territory>`_. For `ET: Legacy <http://www.etlegacy.com>`_ to ever become independent of these paks, there is the need of creating replacements. To keep a proper overview of the process, this documentation includes a full list of all original assets, their state of replacements as well as Legacy-only assets.

Status
======

Displays the status of the asset in Legacy.

*  **"missing"**: Assets from the original game that still need to be replaced in Legacy.
*  **"done"**: Assets that have been replaced already and are in a satisfactory state.
*  **"alpha"**: Assets that have been included as placeholders. To be improved at a later date.
*  **"beta"**: Assets that have been improved, but are likely still subject to change.

Author
======

List of all people involved in the creation of the respective asset for possible future questions.
Sorted alphabetically and limited to 12 chars.

Resources
=========

List of all used resources to avoid any license issues.

Origin
======

The origin of an asset is intended to show where it comes from and why it is part of Legacy.

*  **"pak0"**, **"pak1"**, **"pak2"**: Assets from the original game that had to be replaced for license purposes.
*  **"shader"**: Assets that were specified in shader files in the original game, but had no actual appearance. Rather than removing the shader files, to avoid compatibility issues, the missing assets have been restored.
*  **"[MAP_NAME]"**: Assets that are used in a custom map shipped with Legacy.
*  **"ETL"**: Assets created exclusively for Legacy for various purposes.
*  **"RtCW"**: Due to the similar style, various RtCW assets might be reconstructed and included in Legacy to provide a larger pool for mappers, modders, etc.


-------------
Documentation
-------------


animations
==========

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
human_base.anim                     done     IR4T4                    pak0     29.03.2018
=================================== ======== ============ =========== ======== ============= =============================


human
-----

base
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
akimbo.aninc                        missing                           pak0
akimbo.mdx                          missing                           pak0
binocs.aninc                        missing                           pak0
binocs.mdx                          missing                           pak0
body.aninc                          done     IR4T4        ETPub       pak0     02.02.2015
                                             Spyhawk      ETPro
body.mdx                            missing                           pak0
mortar.aninc                        missing                           pak0
mortar.mdx                          missing                           pak0
no_juice.aninc                      missing                           pak0
no_juice.mdx                        missing                           pak0
prone_dual_pistols.aninc            missing                           pak0
prone_dual_pistols.mdx              missing                           pak0
prone_mortar.aninc                  missing                           pak0
prone_mortar.mdx                    missing                           pak0
prone_pistol.aninc                  missing                           pak0
prone_pistol.mdx                    missing                           pak0
prone_rifle.aninc                   missing                           pak0
prone_rifle.mdx                     missing                           pak0
swim.aninc                          missing                           pak0
swim.mdx                            missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


heads
^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
base.anim                           missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


scripts
-------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
human_base.script                   done     IR4T4        ETPub       pak0     21.09.2016
                                             Spyhawk      ETPro
                                                          NoQuarter
=================================== ======== ============ =========== ======== ============= =============================


botfiles
========

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
botnames.txt                        obsolete                          pak0
chars.h                             obsolete                          pak0
fw_items.c                          obsolete                          pak0
fw_weap.c                           obsolete                          pak0
inv.h                               obsolete                          pak0
items.c                             obsolete                          pak0
match.c                             obsolete                          pak0
match.h                             obsolete                          pak0
rchat.c                             obsolete                          pak0
rnd.c                               obsolete                          pak0
syn.c                               obsolete                          pak0
syn.h                               obsolete                          pak0
teamplay.h                          obsolete                          pak0
weapons.c                           obsolete                          pak0
=================================== ======== ============ =========== ======== ============= =============================


bots
----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
default_c.c                         obsolete                          pak0
default_i.c                         obsolete                          pak0
default_t.c                         obsolete                          pak0
default_w.c                         obsolete                          pak0
=================================== ======== ============ =========== ======== ============= =============================


characters
==========

temperate
---------

allied
^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
cvops.char                          missing                           pak0
engineer.char                       missing                           pak0
fieldops.char                       missing                           pak0
medic.char                          missing                           pak0
soldier.char                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


axis
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
cvops.char                          missing                           pak0
engineer.char                       missing                           pak0
fieldops.char                       missing                           pak0
medic.char                          missing                           pak0
soldier.char                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


configs
=======

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
                                             Dominator56
defaultcomp.config                  done     IR4T4                    ETL      24.01.2016
                                             Jacker
                                             Spyhawk
defaultpublic.config                done     IR4T4                    ETL      16.08.2016
                                             Jacker
                                             Spyhawk
legacy1.config                      done     Dominator56
                                             IR4T4                    ETL      27.02.2017
                                             Jacker
                                             Spyhawk
legacy3.config                      missing                           ETL
legacy5.config                      missing                           ETL
legacy6.config                      missing                           ETL
=================================== ======== ============ =========== ======== ============= =============================


fonts
=====

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
ariblk_0_16.tga                     obsolete                          pak0
ariblk_0_27.tga                     obsolete                          pak0
ariblk_1_27.tga                     obsolete                          pak0
ariblk_16.dat                       obsolete                          pak0
ariblk_27.dat                       obsolete                          pak0
courbd_0_21.tga                     obsolete                          pak0
courbd_0_30.tga                     obsolete                          pak0
courbd_1_30.tga                     obsolete                          pak0
courbd_21.dat                       obsolete                          pak0
courbd_30.dat                       obsolete                          pak0
=================================== ======== ============ =========== ======== ============= =============================


gfx
===

2d
--

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
backtile.jpg                        missing                           pak0
breakablehint.tga                   missing                           pak0
buildhint.tga                       missing                           pak0
classic1.tga                        missing                           pak0
colorbar.tga                        missing                           pak0
compass.tga                         missing                           pak0
compass2.tga                        missing                           pak0
compass_mask.tga                    missing                           pak0
consolechars.tga                    missing                           pak0
crosshaira.tga                      missing                           pak0
crosshaira_alt.tga                  missing                           pak0
crosshairb.tga                      missing                           pak0
crosshairb_alt.tga                  missing                           pak0
crosshairc.tga                      missing                           pak0
crosshaird.tga                      missing                           pak0
crosshaire.tga                      missing                           pak0
crosshairf.tga                      missing                           pak0
crosshairf_alt.tga                  missing                           pak0
crosshairg.tga                      missing                           pak0
crosshairg_alt.tga                  missing                           pak0
crosshairh.tga                      missing                           pak0
crosshairh_alt.tga                  missing                           pak0
crosshairi.tga                      missing                           pak0
crosshairi_alt.tga                  missing                           pak0
crosshairj.tga                      missing                           pak0
crosshairj_alt.tga                  missing                           pak0
disarmhint.tga                      missing                           pak0
doorhint.tga                        missing                           pak0
dynamitehint.tga                    missing                           pak0
friendlycross.tga                   missing                           pak0
hudchars.tga                        missing                           pak0
knife1.tga                          missing                           pak0
knifehint.tga                       missing                           pak0
ladderhint.tga                      missing                           pak0
lag.jpg                             missing                           pak0
landmineHint.tga                    missing                           pak0
lives_allies.tga                    missing                           pak0
lives_axis.tga                      missing                           pak0
lockedhint.tga                      missing                           pak0
minigun1.tga                        missing                           pak0
mp401.tga                           missing                           pak0
multi_dead.tga                      missing                           pak0
net.jpg                             missing                           pak0
notusablehint.tga                   missing                           pak0
pistol1.tga                         missing                           pak0
revivehint.tga                      missing                           pak0
satchelhint.tga                     missing                           pak0
tankHint.tga                        missing                           pak0
uniformHint.tga                     missing                           pak0
usableHint.tga                      missing                           pak0
waterhint.tga                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


numbers
^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
eight_32b.tga                       missing                           pak0
five_32b.tga                        missing                           pak0
four_32b.tga                        missing                           pak0
minus_32b.tga                       missing                           pak0
nine_32b.tga                        missing                           pak0
one_32b.tga                         missing                           pak0
seven_32b.tga                       missing                           pak0
six_32b.tga                         missing                           pak0
slash.tga                           missing                           pak0
three_32b.tga                       missing                           pak0
two_32b.tga                         missing                           pak0
zero_32b.tga                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


colors
------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
ablack.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


damage
------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
bullet_mrk.tga                      missing                           pak0
burn_med_mrk.jpg                    missing                           pak0
glass_mrk.tga                       missing                           pak0
metal_mrk.tga                       missing                           pak0
wood_mrk.tga                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


hud
---

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
ic_health.tga                       missing                           pak0
ic_power.tga                        missing                           pak0
ic_stamina.tga                      missing                           pak0
keyboardkey_old.tga                 missing                           pak0
pm_constallied.tga                  missing                           pak0
pm_constaxis.tga                    missing                           pak0
pm_death.tga                        missing                           pak0
pm_mineallied.tga                   missing                           pak0
pm_mineaxis.tga                     missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


fireteam
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
fireteam1.tga                       missing                           pak0
fireteam2.tga                       missing                           pak0
fireteam3.tga                       missing                           pak0
fireteam4.tga                       missing                           pak0
fireteam5.tga                       missing                           pak0
fireteam6.tga                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


ranks
^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
rank2.tga                           missing                           pak0
rank3.tga                           missing                           pak0
rank4.tga                           missing                           pak0
rank5.tga                           missing                           pak0
rank6.tga                           missing                           pak0
rank7.tga                           missing                           pak0
rank8.tga                           missing                           pak0
rank9.tga                           missing                           pak0
rank10.tga                          missing                           pak0
rank11.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


limbo
-----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
butsur_corn.tga                     missing                           pak0
butsur_hor.tga                      missing                           pak0
butsur_vert.tga                     missing                           pak0
but_objective_dn.tga                missing                           pak0
but_objective_up.tga                missing                           pak0
but_play_off.tga                    missing                           pak0
but_play_on.tga                     missing                           pak0
but_stop_off.tga                    missing                           pak0
but_stop_on.tga                     missing                           pak0
but_team_allied.tga                 missing                           pak0
but_team_axis.tga                   missing                           pak0
but_team_off.tga                    missing                           pak0
but_team_on.tga                     missing                           pak0
but_team_spec.tga                   missing                           pak0
but_weap_off.tga                    missing                           pak0
but_weap_on.tga                     missing                           pak0
cc_blend.tga                        missing                           pak0
cm_alliedgren.tga                   missing                           pak0
cm_axisgren.tga                     missing                           pak0
cm_bankdoor.tga                     missing                           pak0
cm_bo_allied.tga                    missing                           pak0
cm_bo_axis.tga                      missing                           pak0
cm_churchill.tga                    missing                           pak0
cm_constallied.tga                  missing                           pak0
cm_constaxis.tga                    missing                           pak0
cm_dynamite.tga                     missing                           pak0
cm_flagallied.tga                   missing                           pak0
cm_flagaxis.tga                     missing                           pak0
cm_fuel.tga                         missing                           pak0
cm_goldbars.tga                     missing                           pak0
cm_guncontrols.tga                  missing                           pak0
cm_healthammo.tga                   missing                           pak0
cm_jagdpanther.tga                  missing                           pak0
cm_oasiswall.tga                    missing                           pak0
cm_oasis_pakgun.tga                 missing                           pak0
cm_radarbox.tga                     missing                           pak0
cm_radar_maindoor.tga               missing                           pak0
cm_radar_sidedoor.tga               missing                           pak0
cm_satchel.tga                      missing                           pak0
cm_truck.tga                        missing                           pak0
cm_tug.tga                          missing                           pak0
filter_allied.tga                   missing                           pak0
filter_axis.tga                     missing                           pak0
filter_back_off.tga                 missing                           pak0
filter_back_on.tga                  missing                           pak0
filter_bo.tga                       missing                           pak0
filter_construction.tga             missing                           pak0
filter_destruction.tga              missing                           pak0
filter_healthammo.tga               missing                           pak0
filter_objective.tga                missing                           pak0
filter_spawn.tga                    missing                           pak0
flag_allied.tga                     missing                           pak0
flag_axis.tga                       missing                           pak0
ic_battlesense.tga                  missing                           pak0
ic_covertops.tga                    missing                           pak0
ic_engineer.tga                     missing                           pak0
ic_fieldops.tga                     missing                           pak0
ic_lightweap.tga                    missing                           pak0
ic_medic.tga                        missing                           pak0
ic_soldier.tga                      missing                           pak0
lightup_bar.tga                     missing                           pak0
limbo_back.tga                      missing                           pak0
limbo_frame01.tga                   missing                           pak0
limbo_frame02.tga                   missing                           pak0
limbo_frame03.tga                   missing                           pak0
limbo_frame04.tga                   missing                           pak0
limbo_frame05.tga                   missing                           pak0
limbo_frame06.tga                   missing                           pak0
limbo_frame07.tga                   missing                           pak0
limbo_frame08.tga                   missing                           pak0
medals00.tga                        missing                           pak0
medals01.tga                        missing                           pak0
medals02.tga                        missing                           pak0
medals03.tga                        missing                           pak0
medals04.tga                        missing                           pak0
medals05.tga                        missing                           pak0
medals06.tga                        missing                           pak0
medal_back.tga                      missing                           pak0
mort_hit.tga                        missing                           pak0
mort_target.tga                     missing                           pak0
mort_targetarrow.tga                missing                           pak0
number_back.tga                     missing                           pak0
number_border.tga                   missing                           pak0
number_roll.tga                     missing                           pak0
objective_back.tga                  missing                           pak0
objective_back_allied.tga           missing                           pak0
objective_back_axis.tga             missing                           pak0
outofstock.tga                      missing                           pak0
redlight_off.tga                    missing                           pak0
redlight_on.tga                     missing                           pak0
redlight_on02.tga                   missing                           pak0
skill_4pieces.tga                   missing                           pak0
skill_4pieces_off.tga               missing                           pak0
skill_back.tga                      missing                           pak0
skill_back_off.tga                  missing                           pak0
skill_back_on.tga                   missing                           pak0
skill_covops.tga                    missing                           pak0
skill_engineer.tga                  missing                           pak0
skill_fieldops.tga                  missing                           pak0
skill_medic.tga                     missing                           pak0
skill_roll.tga                      missing                           pak0
skill_soldier.tga                   missing                           pak0
spectator.tga                       missing                           pak0
weaponcard01.tga                    missing                           pak0
weaponcard02.tga                    missing                           pak0
weap_blend.tga                      missing                           pak0
weap_card.tga                       missing                           pak0
weap_dnarrow.tga                    missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


loading
-------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
camp_map.tga                        missing                           pak0
camp_side.tga                       missing                           pak0
pin_allied.tga                      missing                           pak0
pin_axis.tga                        missing                           pak0
pin_neutral.tga                     missing                           pak0
pin_shot.tga                        missing                           pak0
progressbar.tga                     missing                           pak0
progressbar_back.tga                missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


misc
----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
binocsimple.tga                     missing                           pak0
flare5.tga                          missing                           pak0
head_open.tga                       missing                           pak0
railcorethin_mono.jpg               missing                           pak0
raindrop.tga                        missing                           pak0
reticle_eq.jpg                      missing                           pak0
smokepuff.tga                       missing                           pak0
smokepuff2b.tga                     missing                           pak0
smokepuffflesh.tga                  missing                           pak0
smokepuffragepro.tga                missing                           pak0
smokepuff_b1.tga                    missing                           pak0
smokepuff_b2.tga                    missing                           pak0
smokepuff_b3.tga                    missing                           pak0
smokepuff_b4.tga                    missing                           pak0
smokepuff_b5.tga                    missing                           pak0
smokepuff_d.tga                     missing                           pak0
snowflake.tga                       missing                           pak0
snow_tri.tga                        missing                           pak0
speaker.tga                         missing                           pak0
speaker_gs.tga                      missing                           pak0
sunflare1.jpg                       missing                           pak0
tracer2.jpg                         missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


icons
=====

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
iconw_ammopack_1_select.tga         missing                           pak0
iconw_binoculars_1_select.tga       missing                           pak0
iconw_browning_1_select.tga         missing                           pak0
iconw_colt_1_select.tga             missing                           pak0
iconw_dynamite_1_select.tga         missing                           pak0
iconw_fg42_1_select.tga             missing                           pak0
iconw_flamethrower_1_select.tga     missing                           pak0
iconw_grenade_1_select.tga          missing                           pak0
iconw_kar98_1_select.tga            missing                           pak0
iconw_knife_1_select.tga            missing                           pak0
iconw_landmine_1_select.tga         missing                           pak0
iconw_luger_1_select.tga            missing                           pak0
iconw_m1_garand_1_select.tga        missing                           pak0
iconw_m1_garand_gren_1_select.tga   missing                           pak0
iconw_mauser_1_select.tga           missing                           pak0
iconw_medheal_select.tga            missing                           pak0
iconw_mg42_1_select.tga             missing                           pak0
iconw_mortar_1_select.tga           missing                           pak0
iconw_MP40_1_select.tga             missing                           pak0
iconw_panzerfaust_1_select.tga      missing                           pak0
iconw_pineapple_1_select.tga        missing                           pak0
iconw_pliers_1_select.tga           missing                           pak0
iconw_radio_1_select.tga            missing                           pak0
iconw_satchel_1_select.tga          missing                           pak0
iconw_silencer_1_select.tga         missing                           pak0
iconw_smokegrenade_1_select.tga     missing                           pak0
iconw_sten_1_select.tga             missing                           pak0
iconw_syringe2_1_select.tga         missing                           pak0
iconw_syringe_1_select.tga          missing                           pak0
iconw_thompson_1_select.tga         missing                           pak0
noammo.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


levelshots
==========

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
battery.tga                         missing                           pak0
battery_cc.tga                      missing                           pak0
fueldump.tga                        missing                           pak0
fueldump_cc.tga                     missing                           pak0
goldrush.tga                        missing                           pak0
goldrush_cc.tga                     missing                           pak0
oasis.tga                           missing                           pak0
oasis_cc.tga                        missing                           pak0
radar.tga                           missing                           pak0
radar_cc.tga                        missing                           pak0
railgun.tga                         missing                           pak0
railgun_cc.tga                      missing                           pak0
unknownmap.tga                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


maps
====

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
battery.bsp                         missing                           pak0
battery.objdata                     missing                           pak0
battery.script                      missing                           pak0
battery_lms.objdata                 missing                           pak0
battery_lms.script                  missing                           pak0
battery_tracemap.tga                missing                           pak0
fueldump.bsp                        missing                           pak0
fueldump.objdata                    missing                           pak0
fueldump.script                     missing                           pak0
fueldump_lms.objdata                missing                           pak0
fueldump_lms.script                 missing                           pak0
fueldump_tracemap.tga               missing                           pak0
goldrush.bsp                        missing                           pak0
goldrush.objdata                    missing                           pak0
goldrush.script                     missing                           pak0
goldrush_lms.objdata                missing                           pak0
goldrush_lms.script                 missing                           pak0
goldrush_tracemap.tga               missing                           pak0
oasis.bsp                           missing                           pak0
oasis.objdata                       missing                           pak0
oasis.script                        missing                           pak0
oasis_lms.objdata                   missing                           pak0
oasis_lms.script                    missing                           pak0
oasis_tracemap.tga                  missing                           pak0
radar.bsp                           missing                           pak0
radar.objdata                       missing                           pak0
radar.script                        missing                           pak0
radar_lms.objdata                   missing                           pak0
radar_lms.script                    missing                           pak0
radar_tracemap.tga                  missing                           pak0
railgun.bsp                         missing                           pak0
railgun.objdata                     missing                           pak0
railgun.script                      missing                           pak0
railgun_lms.objdata                 missing                           pak0
railgun_lms.script                  missing                           pak0
railgun_tracemap.tga                missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


battery
-------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
lm_0000.tga                         missing                           pak0
lm_0001.tga                         missing                           pak0
lm_0002.tga                         missing                           pak0
lm_0003.tga                         missing                           pak0
lm_0004.tga                         missing                           pak0
lm_0005.tga                         missing                           pak0
lm_0006.tga                         missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


fueldump
--------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
lm_0000.tga                         missing                           pak0
lm_0001.tga                         missing                           pak0
lm_0002.tga                         missing                           pak0
lm_0003.tga                         missing                           pak0
lm_0004.tga                         missing                           pak0
lm_0005.tga                         missing                           pak0
lm_0006.tga                         missing                           pak0
lm_0007.tga                         missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


goldrush
--------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
lm_0000.tga                         missing                           pak0
lm_0001.tga                         missing                           pak0
lm_0002.tga                         missing                           pak0
lm_0003.tga                         missing                           pak0
lm_0004.tga                         missing                           pak0
lm_0005.tga                         missing                           pak0
lm_0006.tga                         missing                           pak0
lm_0007.tga                         missing                           pak0
lm_0008.tga                         missing                           pak0
lm_0009.tga                         missing                           pak0
lm_00010.tga                        missing                           pak0
lm_00011.tga                        missing                           pak0
lm_00012.tga                        missing                           pak0
lm_00013.tga                        missing                           pak0
lm_00014.tga                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


oasis
-----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
lm_0000.tga                         missing                           pak0
lm_0001.tga                         missing                           pak0
lm_0002.tga                         missing                           pak0
lm_0003.tga                         missing                           pak0
lm_0004.tga                         missing                           pak0
lm_0005.tga                         missing                           pak0
lm_0006.tga                         missing                           pak0
lm_0007.tga                         missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


radar
-----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
lm_0000.tga                         missing                           pak0
lm_0001.tga                         missing                           pak0
lm_0002.tga                         missing                           pak0
lm_0003.tga                         missing                           pak0
lm_0004.tga                         missing                           pak0
lm_0005.tga                         missing                           pak0
lm_0006.tga                         missing                           pak0
lm_0007.tga                         missing                           pak0
lm_0008.tga                         missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


railgun
-------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
lm_0000.tga                         missing                           pak0
lm_0001.tga                         missing                           pak0
lm_0002.tga                         missing                           pak0
lm_0003.tga                         missing                           pak0
lm_0004.tga                         missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


menu
====


art
---

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
font1_prop.tga                      missing                           pak0
font1_prop_glo.tga                  missing                           pak0
font2_prop.tga                      missing                           pak0
fx_base.tga                         missing                           pak0
fx_blue.tga                         missing                           pak0
fx_cyan.tga                         missing                           pak0
fx_grn.tga                          missing                           pak0
fx_red.tga                          missing                           pak0
fx_teal.tga                         missing                           pak0
fx_white.tga                        missing                           pak0
fx_yel.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


materials
=========

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
                                    missing                           ETL
=================================== ======== ============ =========== ======== ============= =============================


models
======


ammo
----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
grenade1.mdc                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


rocket
^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
panzerfast1a.jpg                    missing                           pak0
rocket.mdc                          missing                           pak0
rockflar.jpg                        missing                           pak0
rockfls2.jpg                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


foliage
-------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
grassfoliage1.tga                   missing                           pak0
grassfoliage2.tga                   missing                           pak0
grassfoliage3.tga                   missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


furniture
---------


barrel
^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
barrel_a.mdc                        missing                           pak0
barrel_m01.jpg                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


chair
^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
chair_office3.mdc                   missing                           pak0
hiback5.mdc                         missing                           pak0
sidechair3.mdc                      missing                           pak0
wood1.jpg                           missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


gibs
----


wood
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
wood1.mdc                           missing                           pak0
wood2.mdc                           missing                           pak0
wood3.mdc                           missing                           pak0
wood4.mdc                           missing                           pak0
wood5.mdc                           missing                           pak0
wood6.mdc                           missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


mapobjects
----------


archeology
^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
vase2.jpg                           missing                           pak0
vase3.jpg                           missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


blitz_sd
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
blitzbody.md3                       missing                           pak0
blitzbody.shadow                    missing                           pak0
blitzbody.tag                       missing                           pak0
blitzbody2.md3                      missing                           pak0
blitzbody3.md3                      missing                           pak0
blitzbody_damaged.MD3               missing                           pak0
blitzbody_damaged.shadow            missing                           pak0
blitzwheelsb.md3                    missing                           pak0
blitzwheelsf.md3                    missing                           pak0
blitz_sd.tga                        missing                           pak0
blitz_sd_interior02.tga             missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


book
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
book.jpg                            missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


cab_sd
^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
part1.tga                           missing                           pak0
part2.tga
trailer.tga
wheels.tga
=================================== ======== ============ =========== ======== ============= =============================


cmarker
^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
allied_cflag.skin                   missing                           pak0
allied_crate.tga                    missing                           pak0
allied_crates.skin                  missing                           pak0
allied_sack.tga                     missing                           pak0
allied_sandbags.skin                missing                           pak0
axis_cflag.skin                     missing                           pak0
axis_crate.tga                      missing                           pak0
axis_crates.skin                    missing                           pak0
axis_sack.tga                       missing                           pak0
axis_sandbags.skin                  missing                           pak0
box_m05.tga                         missing                           pak0
cflagallied.tga                     missing                           pak0
cflagaxis.tga                       missing                           pak0
cflagneutral.tga                    missing                           pak0
cmarker_crates.md3                  missing                           pak0
cmarker_flag.md3                    missing                           pak0
cmarker_sandbags.md3                missing                           pak0
neutral_cflag.skin                  missing                           pak0
neutral_crate.tga                   missing                           pak0
neutral_crates.skin                 missing                           pak0
shovel.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


debris
^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
brick1.mdc                          missing                           pak0
brick2.mdc                          missing                           pak0
brick3.mdc                          missing                           pak0
brick4.mdc                          missing                           pak0
brick5.mdc                          missing                           pak0
brick6.mdc                          missing                           pak0
personal1.mdc                       missing                           pak0
personal2.mdc                       missing                           pak0
personal3.mdc                       missing                           pak0
personal4.mdc                       missing                           pak0
personal5.mdc                       missing                           pak0
personaleffects.jpg                 missing                           pak0
rubble1.mdc                         missing                           pak0
rubble2.mdc                         missing                           pak0
rubble3.mdc                         missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


dinghy_sd
^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
dinghy.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


electronics
^^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
loudspeaker2.jpg                    missing                           pak0
radar_01.tga                        missing                           pak0
tele.jpg                            missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


flag
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
flag_dam.jpg                        missing                           pak0
flag_fg.md3                         missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


furniture
^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
bedlinenpillow_c01.jpg              missing                           pak0
chair1.jpg                          missing                           pak0
chairmetal.jpg                      missing                           pak0
clubchair.jpg                       missing                           pak0
fire.jpg                            missing                           pak0
furnace.jpg                         missing                           pak0
hibackchair_a.jpg                   missing                           pak0
sherman_s.tga                       missing                           pak0
silverware.jpg                      missing                           pak0
trim_c01.jpg                        missing                           pak0
type.tga                            missing                           pak0
wood1.jpg                           missing                           pak0
wood_c05.jpg                        missing                           pak0
xsink.tga                           missing                           pak0
xsink_fac.tga                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


goldbox_sd
^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
goldbox.md3                         missing                           pak0
goldbox.tga                         missing                           pak0
goldbox_trans_red.md3               missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


light
^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
bel_lamp.blend.jpg                  missing                           pak0
bel_lamp.jpg                        missing                           pak0
bel_lamp_2k_gm.md3                  missing                           pak0
bel_lamp_5k_gm.md3                  missing                           pak0
bel_lamp_arm_gm.md3                 missing                           pak0
cagelight.blenda.jpg                missing                           pak0
cagelight.blendr.jpg                missing                           pak0
cagelight_a.jpg                     missing                           pak0
cagelight_r.jpg                     missing                           pak0
cage_light.blendn.jpg               missing                           pak0
cage_lightn.jpg                     missing                           pak0
cage_lightna.tga                    missing                           pak0
chandlier4.tga                      missing                           pak0
chandlier4l.jpg                     missing                           pak0
pendant2.jpg                        missing                           pak0
pendant_sd.jpg                      missing                           pak0
sconce.tga                          missing                           pak0
sconce2.jpg                         missing                           pak0
sconce3.mdc                         missing                           pak0
sd_sconce.tga                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


logs_sd
^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
log.tga                             missing                           pak0
ring.tga                            missing                           pak0
trunk_cut_snow.tga                  missing                           pak0
trunk_snow.tga                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


miltary_trim
^^^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
bags1_s2.tga                        missing                           pak0
barbwire.mdc                        missing                           pak0
dragon_teeth_wils.md3               missing                           pak0
metal_m05.tga                       missing                           pak0
sandbag1_45.md3                     missing                           pak0
sandbag1_45s.md3                    missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


pak75_sd
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
pak75-a.tga                         missing                           pak0
pak75.md3                           missing                           pak0
pak75.tga                           missing                           pak0
pak75_broken.md3                    missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


plants_sd
^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
bush_desert1.tga                    missing                           pak0
bush_desert2.tga                    missing                           pak0
bush_snow1.tga                      missing                           pak0
catail1.tga                         missing                           pak0
catail2.tga                         missing                           pak0
catailfoliage.md3                   missing                           pak0
deadbranch1.tga                     missing                           pak0
deadbranch1_damp.tga                missing                           pak0
deadbranch2.tga                     missing                           pak0
deadbranch3.tga                     missing                           pak0
grassfoliage1.tga                   missing                           pak0
grass_dry3.tga                      missing                           pak0
grass_green1.tga                    missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


portable_radar_sd
^^^^^^^^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
portable_radar_base.md3             missing                           pak0
portable_radar_box.md3              missing                           pak0
portable_radar_box_tr.md3           missing                           pak0
portable_radar_sd.tga               missing                           pak0
portable_radar_top.md3              missing                           pak0
portable_radar_t_sd.tga             missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


props_sd
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
basket.tga                          missing                           pak0
basketsand_empty.md3                missing                           pak0
fuel_can.tga                        missing                           pak0
fuel_can_s.tga                      missing                           pak0
lid.tga                             missing                           pak0
vase.tga                            missing                           pak0
vase_broken_1.md3                   missing                           pak0
xlight_fg2_oasis.md3                missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


pump_sd
^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
bottom.tga                          missing                           pak0
pump_animated.md3                   missing                           pak0
pump_base.md3                       missing                           pak0
top.tga                             missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


radios_sd
^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
allied_sign.tga                     missing                           pak0
axis_sign.tga                       missing                           pak0
beep_blue.tga                       missing                           pak0
beep_gold.tga                       missing                           pak0
beep_green.tga                      missing                           pak0
beep_red.tga                        missing                           pak0
command1.tga                        missing                           pak0
command1a.tga                       missing                           pak0
command2.tga                        missing                           pak0
command3.tga                        missing                           pak0
command4.tga                        missing                           pak0
command5.tga                        missing                           pak0
command6.tga                        missing                           pak0
command7.tga                        missing                           pak0
compostalliedclosed.md3             missing                           pak0
compostalliedclosed.skin            missing                           pak0
compostallieddamaged.md3            missing                           pak0
compostallieddamaged.skin           missing                           pak0
compostalliedopened.md3             missing                           pak0
compostalliedopened.skin            missing                           pak0
compostaxisclosed.md3               missing                           pak0
compostaxisclosed.skin              missing                           pak0
compostaxisdamaged.md3              missing                           pak0
compostaxisdamaged.skin             missing                           pak0
compostaxisopened.md3               missing                           pak0
compostaxisopened.skin              missing                           pak0
compostneutralclosed.md3            missing                           pak0
compostneutralclosed.skin           missing                           pak0
crate.tga                           missing                           pak0
grid.tga                            missing                           pak0
iron.tga                            missing                           pak0
neutral_sign.tga                    missing                           pak0
radio_scroll1.jpg                   missing                           pak0
radio_scroll2.jpg                   missing                           pak0
screen_circle.tga                   missing                           pak0
screen_square.tga                   missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


raster
^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
moto.tga                            missing                           pak0
moto_bag.tga                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


rocks_sd
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
rock_snow.jpg                       missing                           pak0
rock_snow_big.jpg                   missing                           pak0
rock_temperate2.jpg                 missing                           pak0
rock_temperate2_big.jpg             missing                           pak0
rock_temperate2_small.jpg           missing                           pak0
rock_temperate_small.jpg            missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


siwa_props_sd
^^^^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
siwa_pitcher1.jpg                   missing                           pak0
siwa_pitcher2.jpg                   missing                           pak0
siwa_pitcher3.jpg                   missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


spool_sd
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
spool.md3                           missing                           pak0
spool.tga                           missing                           pak0
spool_s.tga                         missing                           pak0
wires.md3                           missing                           pak0
wires.tga                           missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


supplystands
^^^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
frame.tga                           missing                           pak0
metal_shelves.tga                   missing                           pak0
stand_ammo.md3                      missing                           pak0
stand_ammo_damaged.md3              missing                           pak0
stand_health.md3                    missing                           pak0
stand_health_damaged.md3            missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


tanks_sd
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
churchhill.md3                      missing                           pak0
churchhill.shadow                   missing                           pak0
churchhill.tag                      missing                           pak0
churchhill_broken.md3               missing                           pak0
churchhill_broken.shadow            missing                           pak0
churchhill_flash.mdc                missing                           pak0
churchhill_oasis.md3                missing                           pak0
churchhill_oasis.tag                missing                           pak0
churchhill_turret.md3               missing                           pak0
churchhill_turret.tag               missing                           pak0
churchhill_turret_oasis.md3         missing                           pak0
churchill_flat.tga                  missing                           pak0
churchill_flat_oasis.tga            missing                           pak0
jagdpanther_additions_desert.tga    missing                           pak0
jagdpanther_additions_temperate.tga missing                           pak0
jagdpanther_africa_body.md3         missing                           pak0
jagdpanther_africa_shell.md3        missing                           pak0
jagdpanther_africa_shell.shadow     missing                           pak0
jagdpanther_africa_shell.tag        missing                           pak0
jagdpanther_africa_tracks.md3       missing                           pak0
jagdpanther_africa_tracks.tag       missing                           pak0
jagdpanther_africa_tracks2.md3      missing                           pak0
jagdpanther_africa_tracks2.tag      missing                           pak0
jagdpanther_africa_turret.md3       missing                           pak0
jagdpanther_africa_turret.tag       missing                           pak0
jagdpanther_damaged_body.md3        missing                           pak0
jagdpanther_damaged_body.tag        missing                           pak0
jagdpanther_full.tga                missing                           pak0
jagdpanther_full_temperate.tga      missing                           pak0
jagdpanther_temperate_body.md3      missing                           pak0
jagdpanther_temperate_turret.md3    missing                           pak0
mg42.md3                            missing                           pak0
mg42nest.md3                        missing                           pak0
mg42nestbase.md3                    missing                           pak0
mg42turret.tga                      missing                           pak0
mg42turret_2.tga                    missing                           pak0
shadow_tank.tga                     missing                           pak0
tracks.tga                          missing                           pak0
tracks_b.tga                        missing                           pak0
wheel.tga                           missing                           pak0
wheel2_a.tga                        missing                           pak0
wheel_a.tga                         missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


toolshed
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
generator.jpg                       missing                           pak0
shovel_xl.jpg                       missing                           pak0
tools.jpg                           missing                           pak0
weldtanks.jpg                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


tree
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
branch_slp1.tga                     missing                           pak0
branch_slp2.tga                     missing                           pak0
trunck2a.jpg                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


trees_sd
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
winterbranch01.tga                  missing                           pak0
wintertrunk01.tga                   missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


tree_desert_sd
^^^^^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
floorpalmleaf.md3                   missing                           pak0
floorpalmleaf1.md3                  missing                           pak0
palm_leaf1.tga                      missing                           pak0
palm_trunk.tga                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


tree_temperate_sd
^^^^^^^^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
leaves_temperate1.tga               missing                           pak0
leaves_temperate2.tga               missing                           pak0
leaves_temperate3.tga               missing                           pak0
trunk_temperate.tga                 missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


vehicles
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
train1.jpg                          missing                           pak0
wood_m02a.jpg                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


wagon
+++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
wag_whl.tga                         missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


weapons
^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
mg42b.jpg                           missing                           pak0
mg42b.mdc                           missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


xlab
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
cart.jpg                            missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


xlab_props
^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
light.jpg                           missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


multiplayer
-----------


adrenaline
^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
adrenaline.md3                      missing                           pak0
adrenaline_allied.skin              missing                           pak0
adrenaline_axis.skin                missing                           pak0
v_adrenaline.md3                    missing                           pak0
v_adrenaline_hand.md3               missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


ammopack
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
ammopack.md3                        missing                           pak0
ammopack_pickup.md3                 missing                           pak0
ammopack_pickup_s.md3               missing                           pak0
v_ammopack.md3                      missing                           pak0
v_ammopack_hand.md3                 missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


binocs
^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
binocs.md3                          missing                           pak0
binoculars.tga                      missing                           pak0
v_binocs.md3                        missing                           pak0
v_binocs_hand.md3                   missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


browning
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
barrel.tga                          missing                           pak0
browning.tga                        missing                           pak0
tankmounted.md3                     missing                           pak0
thirdperson.md3                     missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


dynamite
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
dynamite.md3                        missing                           pak0
dynamite_3rd.md3                    missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


flagpole
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
american.jpg                        missing                           pak0
flagpole.md3                        missing                           pak0
flag_clouds.tga                     missing                           pak0
flag_waypoint.md3                   missing                           pak0
german.jpg                          missing                           pak0
waypoint.tga                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


gold
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
gold.tga                            missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


kar98
^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
gpg40.tga                           missing                           pak0
kar98_3rd.md3                       missing                           pak0
kar98_3rd_flash.mdc                 missing                           pak0
kar98_allied.skin                   missing                           pak0
kar98_att.md3                       missing                           pak0
kar98_axis.skin                     missing                           pak0
kar98_gren_pickup.md3               missing                           pak0
kar98_scope_pickup.md3              missing                           pak0
kar98_scp.md3                       missing                           pak0
v_kar98.mdc                         missing                           pak0
v_kar98_barrel.mdc                  missing                           pak0
v_kar98_barrel2.mdc                 missing                           pak0
v_kar98_barrel3.mdc                 missing                           pak0
v_kar98_barrel4.mdc                 missing                           pak0
v_kar98_barrel5.mdc                 missing                           pak0
v_kar98_barrel6.mdc                 missing                           pak0
v_kar98_flash.mdc                   missing                           pak0
v_kar98_hand.md3                    missing                           pak0
v_kar98_hand2.md3                   missing                           pak0
v_kar98_scope.md3                   missing                           pak0
v_kar98_scope2.mdc                  missing                           pak0
v_kar98_silencer.md3                missing                           pak0
weapon.cfg                          missing                           pak0
weapon2.cfg                         missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


knife
^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
knife.mdc                           missing                           pak0
knife_allied.skin                   missing                           pak0
knife_axis.skin                     missing                           pak0
v_knife.md3                         missing                           pak0
v_knife_barrel.md3                  missing                           pak0
v_knife_hand.md3                    missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


landmine
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
landmine.jpg                        missing                           pak0
landmine.md3                        missing                           pak0
v_landmine.md3                      missing                           pak0
v_landmine_hand.md3                 missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


m1_garand
^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
m1garandscope_yd.tga                missing                           pak0
m1garandsilencer_yd.tga             missing                           pak0
m1_garand_3rd.md3                   missing                           pak0
m1_garand_3rd_flash.mdc             missing                           pak0
m1_garand_att.md3                   missing                           pak0
m1_garand_gren_pickup.md3           missing                           pak0
m1_garand_prj.md3                   missing                           pak0
m1_garand_scope_pickup.md3          missing                           pak0
m1_garand_scp.md3                   missing                           pak0
m1_garand_yd.tga                    missing                           pak0
rifle2.jpg                          missing                           pak0
s_grenade.tga                       missing                           pak0
s_grenadelauncher.tga               missing                           pak0
v_m1_garand.md3                     missing                           pak0
v_m1_garand_barrel.md3              missing                           pak0
v_m1_garand_barrel2.md3             missing                           pak0
v_m1_garand_barrel3.md3             missing                           pak0
v_m1_garand_barrel4.md3             missing                           pak0
v_m1_garand_barrel5.md3             missing                           pak0
v_m1_garand_barrel6.md3             missing                           pak0
v_m1_garand_flash.mdc               missing                           pak0
v_m1_garand_hand.md3                missing                           pak0
v_m1_garand_hand2.md3               missing                           pak0
v_m1_garand_scope.md3               missing                           pak0
v_m1_garand_scope2.md3              missing                           pak0
v_m1_garand_silencer.md3            missing                           pak0
weapon.cfg                          missing                           pak0
weapon2.cfg                         missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


medpack
^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
medpack.md3                         missing                           pak0
medpack_pickup.md3                  missing                           pak0
v_medpack.md3                       missing                           pak0
v_medpack_hand.md3                  missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


mg42
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
biped.tga                           missing                           pak0
bullet_yd.tga                       missing                           pak0
mg42.md3                            missing                           pak0
mg42_3rd.md3                        missing                           pak0
mg42_3rd_bipod.md3                  missing                           pak0
mg42_3rd_flash.mdc                  missing                           pak0
mg42_allied.skin                    missing                           pak0
mg42_axis.skin                      missing                           pak0
mg42_pickup.md3                     missing                           pak0
s_mg42.tga                          missing                           pak0
v_mg42.md3                          missing                           pak0
v_mg42_barrel.md3                   missing                           pak0
v_mg42_barrel2.md3                  missing                           pak0
v_mg42_barrel3.md3                  missing                           pak0
v_mg42_barrel4.md3                  missing                           pak0
v_mg42_barrel5.md3                  missing                           pak0
v_mg42_barrel6.md3                  missing                           pak0
v_mg42_flash.mdc                    missing                           pak0
v_mg42_hand.md3                     missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


mine_marker
^^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
allied_marker.jpg                   missing                           pak0
allied_marker.md3                   missing                           pak0
axis_marker.jpg                     missing                           pak0
axis_marker.md3                     missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


mortar
^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
mortar_3rd.md3                      missing                           pak0
mortar_3rda.md3                     missing                           pak0
mortar_allied.skin                  missing                           pak0
mortar_axis.skin                    missing                           pak0
mortar_pickup.md3                   missing                           pak0
mortar_sd.tga                       missing                           pak0
mortar_shell.md3                    missing                           pak0
mortar_shell_sd.jpg                 missing                           pak0
v_mortar.md3                        missing                           pak0
v_mortar_barrel.md3                 missing                           pak0
v_mortar_barrel2.md3                missing                           pak0
v_mortar_barrel3.md3                missing                           pak0
v_mortar_barrel4.md3                missing                           pak0
v_mortar_barrel5.md3                missing                           pak0
v_mortar_barrel6.md3                missing                           pak0
v_mortar_barrel7.md3                missing                           pak0
v_mortar_hand.md3                   missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


panzerfaust
^^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
multi_pf.md3                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


pliers
^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
pliers.md3                          missing                           pak0
pliers.tga                          missing                           pak0
pliers_allied.skin                  missing                           pak0
pliers_axis.skin                    missing                           pak0
v_pliers.md3                        missing                           pak0
v_pliers_hand.md3                   missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


satchel
^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
light.md3                           missing                           pak0
lightgreen.tga                      missing                           pak0
lightoff.tga                        missing                           pak0
lightred.tga                        missing                           pak0
needle.md3                          missing                           pak0
radio.md3                           missing                           pak0
radio.tga                           missing                           pak0
satchel.md3                         missing                           pak0
satchel_allied.skin                 missing                           pak0
satchel_allied.tga                  missing                           pak0
satchel_axis.skin                   missing                           pak0
satchel_axis.tga                    missing                           pak0
satchel_world.md3                   missing                           pak0
v_satchel.md3                       missing                           pak0
v_satchel_barrel.md3                missing                           pak0
v_satchel_barrel2.md3               missing                           pak0
v_satchel_hand.md3                  missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


secretdocs
^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
clipboard.tga                       missing                           pak0
paperstack.tga                      missing                           pak0
paperstack2.jpg                     missing                           pak0
secretdocs.md3                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


silencedcolt
^^^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
v_silencedcolt.mdc                  missing                           pak0
v_silencedcolt_barrel.mdc           missing                           pak0
v_silencedcolt_barrel2.mdc          missing                           pak0
v_silencedcolt_barrel3.mdc          missing                           pak0
v_silencedcolt_barrel4.mdc          missing                           pak0
v_silencedcolt_barrel5.mdc          missing                           pak0
v_silencedcolt_barrel6.md3          missing                           pak0
v_silencedcolt_barrel6.mdc          missing                           pak0
v_silencedcolt_barrel7.mdc          missing                           pak0
v_silencedcolt_hand.md3             missing                           pak0  
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


smokebomb
^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
smokebomb.mdc                       missing                           pak0
smoke_bomb.tga                      missing                           pak0
v_smokebomb.mdc                     missing                           pak0
v_smokebomb_hand.mdc                missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


smokegrenade
^^^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
smokegrenade.md3                    missing                           pak0
smoke_grenade.tga                   missing                           pak0
v_smokegrenade.md3                  missing                           pak0
v_smokegrenade_hand.md3             missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


supplies
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
ammobox.tga                         missing                           pak0
ammobox_2.tga                       missing                           pak0
ammobox_wm.md3                      missing                           pak0
healthbox.tga                       missing                           pak0
healthbox_wm.md3                    missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


syringe
^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
fluid.tga                           missing                           pak0
fluid2.tga                          missing                           pak0
fluid3.tga                          missing                           pak0
plunger.tga                         missing                           pak0
syringe.md3                         missing                           pak0
syringe.tga                         missing                           pak0
syringe_allied.skin                 missing                           pak0
syringe_axis.skin                   missing                           pak0
syringe_reflections.tga             missing                           pak0
v_syringe.md3                       missing                           pak0
v_syringe_barrel.md3                missing                           pak0
v_syringe_hand.md3                  missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


players
-------


hud
^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
allied_cvops.skin                   missing                           pak0
allied_cvops.tga                    missing                           pak0
allied_engineer.skin                missing                           pak0
allied_engineer.tga                 missing                           pak0
allied_field.skin                   missing                           pak0
allied_field.tga                    missing                           pak0
allied_medic.skin                   missing                           pak0
allied_medic.tga                    missing                           pak0
allied_soldier.skin                 missing                           pak0
allied_soldier.tga                  missing                           pak0
axis_cvops.skin                     missing                           pak0
axis_cvops.tga                      missing                           pak0
axis_engineer.skin                  missing                           pak0
axis_engineer.tga                   missing                           pak0
axis_field.skin                     missing                           pak0
axis_field.tga                      missing                           pak0
axis_medic.skin                     missing                           pak0
axis_medic.tga                      missing                           pak0
axis_soldier.skin                   missing                           pak0
axis_soldier.tga                    missing                           pak0
eye01.tga                           missing                           pak0
eye02.tga                           missing                           pak0
eye03.tga                           missing                           pak0
head.md3                            missing                           pak0
head_1.md3                          missing                           pak0
teeth01.tga                         missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


damagedskins
++++++++++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
blood01.skin                        missing                           pak0
blood01.tga                         missing                           pak0
blood02.skin                        missing                           pak0
blood02.tga                         missing                           pak0
blood03.skin                        missing                           pak0
blood03.tga                         missing                           pak0
 blood04.skin                       missing                           pak0
blood04.tga                         missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


temparate
^^^^^^^^^


allied
++++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
cap.md3                             missing                           pak0
cap_cvops.skin                      missing                           pak0
helmet.md3                          missing                           pak0
helmet_1.md3                        missing                           pak0
helmet_2.md3                        missing                           pak0
helmet_engineer.skin                missing                           pak0
helmet_fieldops.skin                missing                           pak0
helmet_medic.skin                   missing                           pak0
helmet_soldier.skin                 missing                           pak0
inside.tga                          missing                           pak0
leg01.tga                           missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


cvops
~~~~~

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
body.mdm                            missing                           pak0
body.tga                            missing                           pak0
body_cvops.skin                     missing                           pak0
cap.tga                             missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


engineer
~~~~~~~~

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
body.mdm                            missing                           pak0
body.tga                            missing                           pak0
body_engineer.skin                  missing                           pak0
helmet.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


acc
...

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
backpack.jpg                        missing                           pak0
backpack.md3                        missing                           pak0
shovel.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


fieldops
~~~~~~~~

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
body.mdm                            missing                           pak0
body.tga                            missing                           pak0
body_fieldops.skin                  missing                           pak0
helmet.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


acc
...

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
backpack.md3                        missing                           pak0
backpack.tga                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


medic
~~~~~

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
body.mdm                            missing                           pak0
body.tga                            missing                           pak0
body_medic.skin                     missing                           pak0
helmet.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


acc
...

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
backpack.jpg                        missing                           pak0
backpack.md3                        missing                           pak0
backpack2.jpg                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


soldier
~~~~~~~

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
body.mdm                            missing                           pak0
body.tga                            missing                           pak0
body_soldier.skin                   missing                           pak0
helmet.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


acc
...

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
backpack.jpg                        missing                           pak0
backpack.md3                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


axis
++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
body01.jpg                          missing                           pak0
cap.md3                             missing                           pak0
cap_cvops.skin                      missing                           pak0
helmet.md3                          missing                           pak0
helmet_1.md3                        missing                           pak0
helmet_engineer.skin                missing                           pak0
helmet_fieldops.skin                missing                           pak0
helmet_medic.skin                   missing                           pak0
helmet_soldier.skin                 missing                           pak0
inside.tga                          missing                           pak0
legs01.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


cvops
~~~~~

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
body.mdm                            missing                           pak0
body_cvops.skin                     missing                           pak0
body_cvops.tga                      missing                           pak0
cap.tga                             missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


acc
...

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
backpack.jpg                        missing                           pak0
backpack.md3                        missing                           pak0
fieldkit.tga                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


engineer
~~~~~~~~

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
body.mdm                            missing                           pak0
body_engineer.jpg                   missing                           pak0
body_engineer.skin                  missing                           pak0
helmet.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


acc
...

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
backpack.jpg                        missing                           pak0
backpack.md3                        missing                           pak0
shovel.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


fieldops
~~~~~~~~

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
body.mdm                            missing                           pak0
body_fieldops.skin                  missing                           pak0
body_fieldops.tga                   missing                           pak0
helmet.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


acc
...

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
backpack.jpg                        missing                           pak0
backpack.md3                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


medic
~~~~~

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
axis_medic.tga                      missing                           pak0
body.mdm                            missing                           pak0
body_medic.skin                     missing                           pak0
helmet.tga                          missing                           pak0
legs_medic.jpg                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


acc
...

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
backpack.jpg                        missing                           pak0
backpack.md3                        missing                           pak0
backpack2.tga                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


soldier
~~~~~~~

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
body.mdm                            missing                           pak0
body_soldier.skin                   missing                           pak0
body_soldier.tga                    missing                           pak0
helmet.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


acc
...

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
backpack.jpg                        missing                           pak0
backpack.md3                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


common
++++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
bare_legs.jpg                       missing                           pak0
bare_legs_2.jpg                     missing                           pak0
naked.mdm                           missing                           pak0
naked_allied_cvops.skin             missing                           pak0
naked_allied_engineer.skin          missing                           pak0
naked_allied_fieldops.skin          missing                           pak0
naked_allied_medic.skin             missing                           pak0
naked_allied_soldier.skin           missing                           pak0
naked_axis_cvops.skin               missing                           pak0
naked_axis_engineer.skin            missing                           pak0
naked_axis_fieldops.skin            missing                           pak0
naked_axis_medic.skin               missing                           pak0
naked_axis_soldier.skin             missing                           pak0
rank2.tga                           missing                           pak0
rank3.tga                           missing                           pak0
rank4.tga                           missing                           pak0
rank5.tga                           missing                           pak0
rank6.tga                           missing                           pak0
rank7.tga                           missing                           pak0
rank8.tga                           missing                           pak0
rank9.tga                           missing                           pak0
rank10.tga                          missing                           pak0
rank11.tga                          missing                           pak0
rank_cap.md3                        missing                           pak0
rank_helmet.md3                     missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


powerups
--------


ammo
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
am792mm.jpg                         missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


health
^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
food.jpg                            missing                           pak0
health_t1.mdc                       missing                           pak0
health_t2.mdc                       missing                           pak0
health_t3.mdc                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


holdable
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
binoc.jpg                           missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


shards
------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
fabric1.mdc                         missing                           pak0
fabric2.mdc                         missing                           pak0
fabric3.mdc                         missing                           pak0
glass1.mdc                          missing                           pak0
glass2.mdc                          missing                           pak0
metal.jpg                           missing                           pak0
metal1.mdc                          missing                           pak0
metal2.mdc                          missing                           pak0
wood1.mdc                           missing                           pak0
wood2.mdc                           missing                           pak0
woodshard.jpg                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


weaphits
--------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
blood201.tga                        missing                           pak0
blood202.tga                        missing                           pak0
blood203.tga                        missing                           pak0
blood204.tga                        missing                           pak0
blood205.tga                        missing                           pak0
bullet.mdc                          missing                           pak0
bullet1.tga                         missing                           pak0
bullet2.tga                         missing                           pak0
bullet3.tga                         missing                           pak0
sand_splash.tga                     missing                           pak0
splash2_1.tga                       missing                           pak0
splash2_2.tga                       missing                           pak0
splash2_3.tga                       missing                           pak0
splash2_4.tga                       missing                           pak0
water_splash.tga                    missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


weapons2
--------


akimbo_colt
^^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
v_akimbo_colt.md3                   missing                           pak0
v_akimbo_colt_barrel.md3            missing                           pak0
v_akimbo_colt_barrel2.md3           missing                           pak0
v_akimbo_colt_barrel3.md3           missing                           pak0
v_akimbo_colt_barrel4.md3           missing                           pak0
v_akimbo_colt_barrel5.md3           missing                           pak0
v_akimbo_colt_flash.mdc             missing                           pak0
v_akimbo_colt_hand.md3              missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


akimbo_luger
^^^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
v_akimbo_luger.md3                  missing                           pak0
v_akimbo_luger_barrel.md3           missing                           pak0
v_akimbo_luger_barrel2.md3          missing                           pak0
v_akimbo_luger_barrel3.md3          missing                           pak0
v_akimbo_luger_barrel4.md3          missing                           pak0
v_akimbo_luger_barrel5.md3          missing                           pak0
v_akimbo_luger_flash.mdc            missing                           pak0
v_akimbo_luger_hand.md3             missing                           pak0
v_akimbo_luger_silencer.md3         missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


arms
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
arm_allied.jpg                      missing                           pak0
arm_axis.jpg                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


c4_dynamite
^^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
dynomite1a.tga                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


colt
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
colt_flash.mdc                      missing                           pak0
colt_stand.mdc                      missing                           pak0
colt_yd.tga                         missing                           pak0
silenced.md3                        missing                           pak0
ss_colt.mdc                         missing                           pak0
v_colt.mdc                          missing                           pak0
v_colt_barrel.mdc                   missing                           pak0
v_colt_barrel2.mdc                  missing                           pak0
v_colt_barrel3.mdc                  missing                           pak0
v_colt_barrel4.mdc                  missing                           pak0
v_colt_barrel5.mdc                  missing                           pak0
v_colt_flash.mdc                    missing                           pak0
v_colt_hand.mdc                     missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


dynamite
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
v_dynamite.mdc                      missing                           pak0
v_dynamite_barrel.mdc               missing                           pak0
v_dynamite_hand.mdc                 missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


fg42
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
fg42.md3                            missing                           pak0
fg42_allied.skin                    missing                           pak0
fg42_axis.skin                      missing                           pak0
fg42_barrel.mdc                     missing                           pak0
fg42_flash.mdc                      missing                           pak0
fg42_yd.tga                         missing                           pak0
v_fg42.mdc                          missing                           pak0
v_fg42_barrel2.mdc                  missing                           pak0
v_fg42_barrel3.mdc                  missing                           pak0
v_fg42_barrel4.mdc                  missing                           pak0
v_fg42_flash.mdc                    missing                           pak0
v_fg42_hand.mdc                     missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


flamethrower
^^^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
flame1_yd.tga                       missing                           pak0
flamethrower_flash.mdc              missing                           pak0
flash.jpg                           missing                           pak0
pu_flamethrower.mdc                 missing                           pak0
ss_flamethrower.mdc                 missing                           pak0
v_flamethrower.mdc                  missing                           pak0
v_flamethrower_hand.mdc             missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


grenade
^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
grenade.jpg                         missing                           pak0
grenade_us.tga                      missing                           pak0
grenade_yd.tga                      missing                           pak0
pineapple.mdc                       missing                           pak0
ss_grenade.mdc                      missing                           pak0
ss_pineapple.mdc                    missing                           pak0
v_grenade.mdc                       missing                           pak0
v_grenade_barrel.mdc                missing                           pak0
v_grenade_hand.mdc                  missing                           pak0
v_pineapple.mdc                     missing                           pak0
v_pineapple_barrel.mdc              missing                           pak0
v_pineapple_hand.mdc                missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


knife
^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
arm2.jpg                            missing                           pak0
knife_yd.tga                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


luger
^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
luger7_yd.tga                       missing                           pak0
luger_flash.mdc                     missing                           pak0
luger_stand.mdc                     missing                           pak0
silncer.jpg                         missing                           pak0
ss_luger.mdc                        missing                           pak0
v_luger.mdc                         missing                           pak0
v_luger_barrel.mdc                  missing                           pak0  
v_luger_barrel2.mdc                 missing                           pak0
v_luger_barrel3.mdc                 missing                           pak0
v_luger_barrel4.mdc                 missing                           pak0
v_luger_flash.mdc                   missing                           pak0
v_luger_hand.mdc                    missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


machinegun
^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
f_machinegun.tga                    missing                           pak0
f_machinegun1.tga                   missing                           pak0
mg42_flash.mdc                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


mauser
^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
mauser3_yd.tga                      missing                           pak0
mauserif5.jpg                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


mp40
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
gun11_yd.tga                        missing                           pak0
hand16.jpg                          missing                           pak0
mp40.mdc                            missing                           pak0
mp40_allied.skin                    missing                           pak0
mp40_axis.skin                      missing                           pak0
mp40_flash.mdc                      missing                           pak0
mp40_stand.mdc                      missing                           pak0
ss_mp40.mdc                         missing                           pak0
v_mp40.mdc                          missing                           pak0
v_mp40_barrel.mdc                   missing                           pak0
v_mp40_barrel2.mdc                  missing                           pak0
v_mp40_barrel3.mdc                  missing                           pak0
v_mp40_flash.mdc                    missing                           pak0
v_mp40_hand.mdc                     missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


panzerfaust
^^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
panzerfast1a.jpg                    missing                           pak0
panzerfaust_yd.tga                  missing                           pak0
pf.mdc                              missing                           pak0
pf_flash.mdc                        missing                           pak0
pf_stand.mdc                        missing                           pak0
v_pf.mdc                            missing                           pak0
v_pf_barrel.mdc                     missing                           pak0
v_pf_barrel2.mdc                    missing                           pak0
v_pf_barrel3.mdc                    missing                           pak0
v_pf_barrel4.mdc                    missing                           pak0
v_pf_barrel5.mdc                    missing                           pak0
v_pf_flash.mdc                      missing                           pak0
v_pf_hand.mdc                       missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


rocketl
^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
f_rocketl.jpg                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


shells
^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
M_shell.jpg                         missing                           pak0
m_shell.mdc                         missing                           pak0
pf_shell.mdc                        missing                           pak0
sm_shell.mdc                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


silencer
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
silencer.mdc                        missing                           pak0
silencer_stand.mdc                  missing                           pak0
v_silencer.mdc                      missing                           pak0
v_silencer_barrel.mdc               missing                           pak0
v_silencer_barrel2.mdc              missing                           pak0
v_silencer_barrel3.mdc              missing                           pak0
v_silencer_barrel4.mdc              missing                           pak0
v_silencer_barrel5.mdc              missing                           pak0
v_silencer_barrel6.mdc              missing                           pak0
v_silencer_hand.mdc                 missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


sten
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
ss_sten.mdc                         missing                           pak0
sten.mdc                            missing                           pak0
sten1_yd.tga                        missing                           pak0
sten_stand.mdc                      missing                           pak0
v_sten.mdc                          missing                           pak0
v_sten_barrel.mdc                   missing                           pak0
v_sten_barrel2.mdc                  missing                           pak0
v_sten_barrel3.mdc                  missing                           pak0
v_sten_hand.mdc                     missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


thompson
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
thompson.mdc                        missing                           pak0
thompson_allied.skin                missing                           pak0
thompson_axis.skin                  missing                           pak0
thompson_flash.mdc                  missing                           pak0
thompson_la_yd.tga                  missing                           pak0
thompson_stand.mdc                  missing                           pak0
v_thompson.mdc                      missing                           pak0
v_thompson_barrel.mdc               missing                           pak0
v_thompson_barrel2.mdc              missing                           pak0
v_thompson_barrel3.mdc              missing                           pak0
v_thompson_flash.mdc                missing                           pak0
v_thompson_hand.mdc                 missing                           pak0
weapon.cfg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


scripts
=======

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
alpha.shader                        missing                           pak0
alpha_sd.shader                     missing                           pak0
assault.shader                      missing                           pak0
assault_rock.shader                 missing                           pak0
awf_props.shader                    missing                           pak0
battery.arena                       missing                           pak0
battery.shader                      missing                           pak0
battery_wall.shader                 missing                           pak0
bbmodels_mapobjects.shader          missing                           pak0
blimp.shader                        missing                           pak0
bots.txt                            missing                           pak0
bunker_sd.shader                    missing                           pak0
castle_door.shader                  missing                           pak0
castle_floor.shader                 missing                           pak0
castle_window.shader                missing                           pak0
castle_wood.shader                  missing                           pak0
centraleurope.campaign              missing                           pak0
chat.shader                         missing                           pak0
chateau.shader                      missing                           pak0
chat_window.shader                  missing                           pak0
chat_wood.shader                    missing                           pak0
common.shader                       missing                           pak0
decals.shader                       missing                           pak0
doors.shader                        missing                           pak0
eerie.shader                        missing                           pak0
egypt_door_sd.shader                missing                           pak0
egypt_floor_sd.shader               missing                           pak0
egypt_props_sd.shader               missing                           pak0
egypt_rock_sd.shader                missing                           pak0
egypt_trim_sd.shader                missing                           pak0
egypt_walls_sd.shader               missing                           pak0
egypt_windows_sd.shader             missing                           pak0
egypt_wood_sd.shader                missing                           pak0
factory_sd.shader                   missing                           pak0
fueldump.arena                      missing                           pak0
fueldump.shader                     missing                           pak0
gfx_2d.shader                       missing                           pak0
gfx_clipboard.shader                missing                           pak0
gfx_damage.shader                   missing                           pak0
gfx_hud.shader                      missing                           pak0
gfx_limbo.shader                    missing                           pak0
gfx_misc.shader                     missing                           pak0
goldrush.arena                      missing                           pak0
goldrush.shader                     missing                           pak0
icons.shader                        missing                           pak0
levelshots.shader                   missing                           pak0
lights.shader                       missing                           pak0
liquids.shader                      missing                           pak0
liquids_sd.shader                   missing                           pak0
mapfx.shader                        missing                           pak0
metals_sd.shader                    missing                           pak0
metal_misc.shader                   missing                           pak0
miltary_door.shader                 missing                           pak0
miltary_trim.shader                 missing                           pak0
miltary_wall.shader                 missing                           pak0
models_ammo.shader                  missing                           pak0
models_foliage.shader               missing                           pak0
models_furniture.shader             missing                           pak0
models_mapobjects.shader            missing                           pak0
models_multiplayer.shader           missing                           pak0
models_players.shader               missing                           pak0
models_shards.shader                missing                           pak0
models_weapons2.shader              missing                           pak0
mp_goldrush.shader                  missing                           pak0
mp_guns.shader                      missing                           pak0
mp_railgun.shader                   missing                           pak0
mp_rocket.shader                    missing                           pak0
mp_seawall.shader                   missing                           pak0
mp_siwa.shader                      missing                           pak0
mp_wurzburg.shader                  missing                           pak0
northafrican.campaign               missing                           pak0
oasis.arena                         missing                           pak0
props.shader                        missing                           pak0
props_sd.shader                     missing                           pak0
radar.arena                         missing                           pak0
radar.shader                        missing                           pak0
railgun.arena                       missing                           pak0
railgun_props.shader                missing                           pak0
railway_sd.shader                   missing                           pak0
rock.shader                         missing                           pak0
rubble.shader                       missing                           pak0
seawall_wall.shader                 missing                           pak0
sfx.shader                          missing                           pak0
shadows.shader                      missing                           pak0
siwa_fx_sd.shader                   missing                           pak0
siwa_props_sd.shader                missing                           pak0
siwa_skyboxes_sd.shader             missing                           pak0
skies.shader                        missing                           pak0
snow.shader                         missing                           pak0
snow_sd.shader                      missing                           pak0
sprites.shader                      missing                           pak0
stone.shader                        missing                           pak0
swf.shader                          missing                           pak0
temperate_sd.shader                 missing                           pak0
terrain.shader                      missing                           pak0
textures.shader                     missing                           pak0
tobruk_wall_sd.shader               missing                           pak0
tobruk_windows_sd.shader            missing                           pak0
town_props.shader                   missing                           pak0
town_roof.shader                    missing                           pak0
town_wall.shader                    missing                           pak0
town_window.shader                  missing                           pak0
town_wood.shader                    missing                           pak0
tree.shader                         missing                           pak0
ui_assets.shader                    missing                           pak0
ui_assets2.shader                   missing                           pak0
village.shader                      missing                           pak0
villa_sd.shader                     missing                           pak0
wm_allies_chat.voice                missing                           pak0
wm_axis_chat.voice                  missing                           pak0
wood.shader                         missing                           pak0
xlab_door.shader                    missing                           pak0
xlab_props.shader                   missing                           pak0
xlab_wall.shader                    missing                           pak0
_unsorted.shader                    missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


sound
=====


chat
----


allies
^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
10a.wav                             missing                           pak0
10b.wav                             missing                           pak0
11a.wav                             missing                           pak0
11b.wav                             missing                           pak0
12a.wav                             missing                           pak0
12b.wav                             missing                           pak0
13a.wav                             missing                           pak0
13b.wav                             missing                           pak0
14a.wav                             missing                           pak0
14b.wav                             missing                           pak0
15a.wav                             missing                           pak0
15b.wav                             missing                           pak0
16a.wav                             missing                           pak0
16b.wav                             missing                           pak0
17a.wav                             missing                           pak0
17b.wav                             missing                           pak0
18a.wav                             missing                           pak0
18b.wav                             missing                           pak0
19a.wav                             missing                           pak0
19b.wav                             missing                           pak0
21a.wav                             missing                           pak0
21b.wav                             missing                           pak0
22a.wav                             missing                           pak0
23a.wav                             missing                           pak0
23b.wav                             missing                           pak0
24a.wav                             missing                           pak0
24b.wav                             missing                           pak0
25a.wav                             missing                           pak0
25b.wav                             missing                           pak0
25c.wav                             missing                           pak0
25d.wav                             missing                           pak0
26a.wav                             missing                           pak0
26b.wav                             missing                           pak0
27a.wav                             missing                           pak0
27b.wav                             missing                           pak0
28a.wav                             missing                           pak0
28b.wav                             missing                           pak0
31a.wav                             missing                           pak0
31b.wav                             missing                           pak0
32a.wav                             missing                           pak0
32b.wav                             missing                           pak0
33a.wav                             missing                           pak0
33b.wav                             missing                           pak0
34a.wav                             missing                           pak0
34b.wav                             missing                           pak0
35a.wav                             missing                           pak0
35b.wav                             missing                           pak0
36a.wav                             missing                           pak0
36b.wav                             missing                           pak0
37a.wav                             missing                           pak0
37b.wav                             missing                           pak0
38a.wav                             missing                           pak0
38b.wav                             missing                           pak0
39a.wav                             missing                           pak0
39b.wav                             missing                           pak0
41a.wav                             missing                           pak0
41b.wav                             missing                           pak0
41c.wav                             missing                           pak0
42a.wav                             missing                           pak0
42b.wav                             missing                           pak0
42c.wav                             missing                           pak0
42d.wav                             missing                           pak0
43a.wav                             missing                           pak0
43b.wav                             missing                           pak0
43c.wav                             missing                           pak0
43d.wav                             missing                           pak0
44a.wav                             missing                           pak0
44b.wav                             missing                           pak0
44c.wav                             missing                           pak0
44d.wav                             missing                           pak0
45a.wav                             missing                           pak0
45b.wav                             missing                           pak0
45c.wav                             missing                           pak0
46a.wav                             missing                           pak0
46b.wav                             missing                           pak0
46c.wav                             missing                           pak0
54a.wav                             missing                           pak0
54b.wav                             missing                           pak0
54c.wav                             missing                           pak0
54d.wav                             missing                           pak0
54e.wav                             missing                           pak0
55a.wav                             missing                           pak0
55b.wav                             missing                           pak0
55c.wav                             missing                           pak0
55d.wav                             missing                           pak0
55e.wav                             missing                           pak0
56a.wav                             missing                           pak0
56b.wav                             missing                           pak0
57a.wav                             missing                           pak0
57b.wav                             missing                           pak0
57c.wav                             missing                           pak0
57d.wav                             missing                           pak0
57e.wav                             missing                           pak0
57f.wav                             missing                           pak0
57g.wav                             missing                           pak0
57h.wav                             missing                           pak0
57i.wav                             missing                           pak0
57j.wav                             missing                           pak0
57k.wav                             missing                           pak0
57l.wav                             missing                           pak0
61a.wav                             missing                           pak0
61b.wav                             missing                           pak0
62a.wav                             missing                           pak0
62b.wav                             missing                           pak0
63a.wav                             missing                           pak0
63b.wav                             missing                           pak0
64a.wav                             missing                           pak0
65a.wav                             missing                           pak0
71a.wav                             missing                           pak0
71b.wav                             missing                           pak0
72a.wav                             missing                           pak0
72b.wav                             missing                           pak0
73a.wav                             missing                           pak0
73b.wav                             missing                           pak0
75a.wav                             missing                           pak0
75b.wav                             missing                           pak0
76a.wav                             missing                           pak0
76b.wav                             missing                           pak0
77a.wav                             missing                           pak0
77b.wav                             missing                           pak0
81a.wav                             missing                           pak0
81b.wav                             missing                           pak0
81c.wav                             missing                           pak0
81d.wav                             missing                           pak0
82a.wav                             missing                           pak0
82b.wav                             missing                           pak0
82c.wav                             missing                           pak0
82d.wav                             missing                           pak0
83a.wav                             missing                           pak0
83b.wav                             missing                           pak0
84a.wav                             missing                           pak0
84b.wav                             missing                           pak0
98a.wav                             missing                           pak0
98b.wav                             missing                           pak0
99a.wav                             missing                           pak0
99b.wav                             missing                           pak0
586a.wav                            missing                           pak0
586b.wav                            missing                           pak0
586c.wav                            missing                           pak0
911a.wav                            missing                           pak0
911b.wav                            missing                           pak0
921a.wav                            missing                           pak0
921b.wav                            missing                           pak0
922a.wav                            missing                           pak0
923a.wav                            missing                           pak0
923b.wav                            missing                           pak0
924a.wav                            missing                           pak0
924b.wav                            missing                           pak0
931a.wav                            missing                           pak0
931b.wav                            missing                           pak0
932a.wav                            missing                           pak0
932b.wav                            missing                           pak0
933a.wav                            missing                           pak0
933b.wav                            missing                           pak0
934a.wav                            missing                           pak0
934b.wav                            missing                           pak0
935a.wav                            missing                           pak0
935b.wav                            missing                           pak0
941a.wav                            missing                           pak0
941b.wav                            missing                           pak0
942a.wav                            missing                           pak0
942b.wav                            missing                           pak0
944a.wav                            missing                           pak0
944b.wav                            missing                           pak0
945a.wav                            missing                           pak0
945b.wav                            missing                           pak0
951a.wav                            missing                           pak0
951b.wav                            missing                           pak0
952a.wav                            missing                           pak0
953a.wav                            missing                           pak0
953b.wav                            missing                           pak0
954a.wav                            missing                           pak0
955a.wav                            missing                           pak0
medic.wav                           missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================



axis
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
10a.wav                             missing                           pak0
10b.wav                             missing                           pak0
11a.wav                             missing                           pak0
11b.wav                             missing                           pak0
12a.wav                             missing                           pak0
12b.wav                             missing                           pak0
13a.wav                             missing                           pak0
13b.wav                             missing                           pak0
14a.wav                             missing                           pak0
14b.wav                             missing                           pak0
15a.wav                             missing                           pak0
15b.wav                             missing                           pak0
16a.wav                             missing                           pak0
16b.wav                             missing                           pak0
17a.wav                             missing                           pak0
17b.wav                             missing                           pak0
18a.wav                             missing                           pak0
18b.wav                             missing                           pak0
19a.wav                             missing                           pak0
19b.wav                             missing                           pak0
21a.wav                             missing                           pak0
21b.wav                             missing                           pak0
22a.wav                             missing                           pak0
23a.wav                             missing                           pak0
23b.wav                             missing                           pak0
24a.wav                             missing                           pak0
24b.wav                             missing                           pak0
25a.wav                             missing                           pak0
25b.wav                             missing                           pak0
25c.wav                             missing                           pak0
25d.wav                             missing                           pak0
26a.wav                             missing                           pak0
26b.wav                             missing                           pak0
27a.wav                             missing                           pak0
27b.wav                             missing                           pak0
28a.wav                             missing                           pak0
28b.wav                             missing                           pak0
31a.wav                             missing                           pak0
31b.wav                             missing                           pak0
32a.wav                             missing                           pak0
32b.wav                             missing                           pak0
33a.wav                             missing                           pak0
33b.wav                             missing                           pak0
34a.wav                             missing                           pak0
34b.wav                             missing                           pak0
35a.wav                             missing                           pak0
35b.wav                             missing                           pak0
36a.wav                             missing                           pak0
36b.wav                             missing                           pak0
37a.wav                             missing                           pak0
37b.wav                             missing                           pak0
38a.wav                             missing                           pak0
38b.wav                             missing                           pak0
39a.wav                             missing                           pak0
39b.wav                             missing                           pak0
41a.wav                             missing                           pak0
41b.wav                             missing                           pak0
41c.wav                             missing                           pak0
42a.wav                             missing                           pak0
42b.wav                             missing                           pak0
42c.wav                             missing                           pak0
43a.wav                             missing                           pak0
43b.wav                             missing                           pak0
43c.wav                             missing                           pak0
44a.wav                             missing                           pak0
44b.wav                             missing                           pak0
44c.wav                             missing                           pak0
45a.wav                             missing                           pak0
45b.wav                             missing                           pak0
46a.wav                             missing                           pak0
46b.wav                             missing                           pak0
54a.wav                             missing                           pak0
54b.wav                             missing                           pak0
54c.wav                             missing                           pak0
55a.wav                             missing                           pak0
55b.wav                             missing                           pak0
55c.wav                             missing                           pak0
56a.wav                             missing                           pak0
56b.wav                             missing                           pak0
57a.wav                             missing                           pak0
57b.wav                             missing                           pak0
57c.wav                             missing                           pak0
57d.wav                             missing                           pak0
57e.wav                             missing                           pak0
57f.wav                             missing                           pak0
57g.wav                             missing                           pak0
57h.wav                             missing                           pak0
61a.wav                             missing                           pak0
61b.wav                             missing                           pak0
62a.wav                             missing                           pak0
62b.wav                             missing                           pak0
63a.wav                             missing                           pak0
63b.wav                             missing                           pak0
64a.wav                             missing                           pak0
64b.wav                             missing                           pak0
65a.wav                             missing                           pak0
71a.wav                             missing                           pak0
71b.wav                             missing                           pak0
72a.wav                             missing                           pak0
72b.wav                             missing                           pak0
73a.wav                             missing                           pak0
73b.wav                             missing                           pak0
75a.wav                             missing                           pak0
75b.wav                             missing                           pak0
76a.wav                             missing                           pak0
76b.wav                             missing                           pak0
77a.wav                             missing                           pak0
77b.wav                             missing                           pak0
81a.wav                             missing                           pak0
81b.wav                             missing                           pak0
82a.wav                             missing                           pak0
82b.wav                             missing                           pak0
83a.wav                             missing                           pak0
83b.wav                             missing                           pak0
84a.wav                             missing                           pak0
84b.wav                             missing                           pak0
98a.wav                             missing                           pak0
98b.wav                             missing                           pak0
98c.wav                             missing                           pak0
99a.wav                             missing                           pak0
586a.wav                            missing                           pak0
586b.wav                            missing                           pak0
911a.wav                            missing                           pak0
911b.wav                            missing                           pak0
921a.wav                            missing                           pak0
921b.wav                            missing                           pak0
922a.wav                            missing                           pak0
922b.wav                            missing                           pak0
923a.wav                            missing                           pak0
923b.wav                            missing                           pak0
924a.wav                            missing                           pak0
924b.wav                            missing                           pak0
931a.wav                            missing                           pak0
931b.wav                            missing                           pak0
932a.wav                            missing                           pak0
932b.wav                            missing                           pak0
933a.wav                            missing                           pak0
933b.wav                            missing                           pak0
934a.wav                            missing                           pak0
934b.wav                            missing                           pak0
935a.wav                            missing                           pak0
935b.wav                            missing                           pak0
941a.wav                            missing                           pak0
941b.wav                            missing                           pak0
942a.wav                            missing                           pak0
942b.wav                            missing                           pak0
944a.wav                            missing                           pak0
944b.wav                            missing                           pak0
945a.wav                            missing                           pak0
945b.wav                            missing                           pak0
951a.wav                            missing                           pak0
951b.wav                            missing                           pak0
952a.wav                            missing                           pak0
952b.wav                            missing                           pak0
953a.wav                            missing                           pak0
953b.wav                            missing                           pak0
954a.wav                            missing                           pak0
954b.wav                            missing                           pak0
955a.wav                            missing                           pak0
955b.wav                            missing                           pak0
medic.wav                           missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


maps
----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
battery.sps                         missing                           pak0
expl_large.wav                      missing                           pak0
expl_med.wav                        missing                           pak0
expl_small.wav                      missing                           pak0
fueldump.sps                        missing                           pak0
goldrush.sps                        missing                           pak0
gun_fire.wav                        missing                           pak0
oasis.sps                           missing                           pak0
radar.sps                           missing                           pak0
railgun.sps                         missing                           pak0
track_move.wav                      missing                           pak0
track_switch.wav                    missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


menu
----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
cancel.wav                          missing                           pak0
filter.wav                          missing                           pak0
select.wav                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


misc
----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
am_pkup.wav                         missing                           pak0
bag_toss.wav                        missing                           pak0
body_pickup.wav                     missing                           pak0
health_pickup.wav                   missing                           pak0
rank_up.wav                         missing                           pak0
referee.wav                         missing                           pak0
skill_up.wav                        missing                           pak0
vote.wav                            missing                           pak0
vo_revive.wav                       missing                           pak0
w_pkup.wav                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


movers
------


doors
^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
default_door_locked.wav             missing                           pak0
door2_close.wav                     missing                           pak0
door2_locked.wav                    missing                           pak0
door2_open.wav                      missing                           pak0
door4_close.wav                     missing                           pak0
door4_endc.wav                      missing                           pak0
door4_endcq.wav                     missing                           pak0
door4_kicked.wav                    missing                           pak0
door4_kickedend.wav                 missing                           pak0
door4_locked.wav                    missing                           pak0
door4_open.wav                      missing                           pak0
door4_openq.wav                     missing                           pak0
door5_close.wav                     missing                           pak0
door5_endc.wav                      missing                           pak0
door5_kicked.wav                    missing                           pak0
door5_kickedend.wav                 missing                           pak0
door5_locked.wav                    missing                           pak0
door5_open.wav                      missing                           pak0
door6_close.wav                     missing                           pak0
door6_endc.wav                      missing                           pak0
door6_locked.wav                    missing                           pak0
door6_loopc.wav                     missing                           pak0
door6_loopo.wav                     missing                           pak0
door6_open.wav                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


misc
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
big_gate1.wav                       missing                           pak0
big_gate2.wav                       missing                           pak0
big_gate3.wav                       missing                           pak0
garage_door_end_01.wav              missing                           pak0
garage_door_loop_01.wav             missing                           pak0
garage_door_start_01.wav            missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


motors
^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
motor_end_01.wav                    missing                           pak0
motor_end_02.wav                    missing                           pak0
motor_loop_01.wav                   missing                           pak0
motor_loop_02.wav                   missing                           pak0
motor_loop_03.wav                   missing                           pak0
motor_start_01.wav                  missing                           pak0
motor_start_02.wav                  missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


switches
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
butn2.wav                           missing                           pak0
switch.wav                          missing                           pak0
switch_01.wav                       missing                           pak0
switch_02.wav                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


music
-----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
allies_win.wav                      missing                           pak0
axis_win.wav                        missing                           pak0
menu_server.wav                     missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


player
------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
gasp.wav                            missing                           pak0
gib.wav                             missing                           pak0
gurp1.wav                           missing                           pak0
gurp2.wav                           missing                           pak0
hurt_barbwire.wav                   missing                           pak0
land_hurt.wav                       missing                           pak0
underwater.wav                      missing                           pak0
water_in.wav                        missing                           pak0
water_out.wav                       missing                           pak0
water_un.wav                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


default
^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
blank.wav                           missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


footsteps
^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
carpet1.wav                         missing                           pak0
carpet2.wav                         missing                           pak0
carpet3.wav                         missing                           pak0
carpet4.wav                         missing                           pak0
carpet_jump.wav                     missing                           pak0
grass1.wav                          missing                           pak0
grass2.wav                          missing                           pak0
grass3.wav                          missing                           pak0
grass4.wav                          missing                           pak0
grass_jump.wav                      missing                           pak0
gravel1.wav                         missing                           pak0
gravel2.wav                         missing                           pak0
gravel3.wav                         missing                           pak0
gravel4.wav                         missing                           pak0
gravel_jump.wav                     missing                           pak0
metal1.wav                          missing                           pak0
metal2.wav                          missing                           pak0
metal3.wav                          missing                           pak0
metal4.wav                          missing                           pak0
metal_jump.wav                      missing                           pak0
roof1.wav                           missing                           pak0
roof2.wav                           missing                           pak0
roof3.wav                           missing                           pak0
roof4.wav                           missing                           pak0
roof_jump.wav                       missing                           pak0
snow1.wav                           missing                           pak0
snow2.wav                           missing                           pak0
snow3.wav                           missing                           pak0
snow4.wav                           missing                           pak0
snow_jump.wav                       missing                           pak0
stone1.wav                          missing                           pak0
stone2.wav                          missing                           pak0
stone3.wav                          missing                           pak0
stone4.wav                          missing                           pak0
stone_jump.wav                      missing                           pak0
water1.wav                          missing                           pak0
water2.wav                          missing                           pak0
water3.wav                          missing                           pak0
water4.wav                          missing                           pak0
water_jump.wav                      missing                           pak0
wood1.wav                           missing                           pak0
wood2.wav                           missing                           pak0
wood3.wav                           missing                           pak0
wood4.wav                           missing                           pak0
wood_jump.wav                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


scripts
-------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
battery.sounds                      missing                           pak0
filelist.txt                        missing                           pak0
fueldump.sounds                     missing                           pak0
goldrush.sounds                     missing                           pak0
oasis.sounds                        missing                           pak0
radar.sounds                        missing                           pak0
railgun.sounds                      missing                           pak0
vo_allies.sounds                    missing                           pak0
vo_axis.sounds                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


vehicles
--------


misc
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
radar_end.wav                       missing                           pak0
radar_loop.wav                      missing                           pak0
radar_start.wav                     missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


tank
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
tank_fire.wav                       missing                           pak0
tank_idle.wav                       missing                           pak0
tank_move.wav                       missing                           pak0
tank_revdown.wav                    missing                           pak0
tank_revup.wav                      missing                           pak0
tank_start.wav                      missing                           pak0
tank_stop.wav                       missing                           pak0
turret_end.wav                      missing                           pak0
turret_spin.wav                     missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


truck
^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
truck_idle.wav                      missing                           pak0
truck_move.wav                      missing                           pak0
truck_revdown.wav                   missing                           pak0
truck_revup.wav                     missing                           pak0
truck_start.wav                     missing                           pak0
truck_stop.wav                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


tug
^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
tug_idle.wav                        missing                           pak0
tug_move.wav                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


vo
--


battery
^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
news_battery.wav                    missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


allies
++++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
hq_bunkercap.wav                    missing                           pak0
hq_bunkercapd.wav                   missing                           pak0
hq_bunkerrecl.wav                   missing                           pak0
hq_gendest.wav                      missing                           pak0
hq_gendyn.wav                       missing                           pak0
hq_gunctrldyn.wav                   missing                           pak0
hq_rampcon.wav                      missing                           pak0
hq_rampconst.wav                    missing                           pak0
hq_rampdest.wav                     missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


axis
++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
hq_beacheadv.wav                    missing                           pak0
hq_beachwadv.wav                    missing                           pak0
hq_bunkercap.wav                    missing                           pak0
hq_bunkerdef.wav                    missing                           pak0
hq_bunkerrecl.wav                   missing                           pak0
hq_genconst.wav                     missing                           pak0
hq_gendef.wav                       missing                           pak0
hq_gendest.wav                      missing                           pak0
hq_gunctrldef.wav                   missing                           pak0
hq_rampconst.wav                    missing                           pak0
hq_rampdest.wav                     missing                           pak0
hq_rampstop.wav                     missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


fueldump
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
news_fueldump.wav                   missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


allies
++++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
hq_bridgecon.wav                    missing                           pak0
hq_bridgeconst.wav                  missing                           pak0
hq_bridgedam.wav                    missing                           pak0
hq_bridgedest.wav                   missing                           pak0
hq_bridgereinf.wav                  missing                           pak0
hq_bridgereinfd.wav                 missing                           pak0
hq_depotdest.wav                    missing                           pak0
hq_depotdyn.wav                     missing                           pak0
hq_dumpdyn.wav                      missing                           pak0
hq_gatesdest.wav                    missing                           pak0
hq_gratedest.wav                    missing                           pak0
hq_tankbridge.wav                   missing                           pak0
hq_tankgates.wav                    missing                           pak0
hq_tankrear.wav                     missing                           pak0
hq_tunneldest.wav                   missing                           pak0
hq_walldest.wav                     missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


axis
++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
hq_bridgeconst.wav                  missing                           pak0
hq_bridgedam.wav                    missing                           pak0
hq_bridgedest.wav                   missing                           pak0
hq_bridgereinf.wav                  missing                           pak0
hq_bridgerep.wav                    missing                           pak0
hq_bridgestop.wav                   missing                           pak0
hq_depotbreach.wav                  missing                           pak0
hq_depotcon.wav                     missing                           pak0
hq_depotconst.wav                   missing                           pak0
hq_depotdest.wav                    missing                           pak0
hq_dumpdef.wav                      missing                           pak0
hq_gatesdest.wav                    missing                           pak0
hq_gatesstop.wav                    missing                           pak0
hq_gratedest.wav                    missing                           pak0
hq_tankbridge.wav                   missing                           pak0
hq_tanktunnels.wav                  missing                           pak0
hq_tunneldest.wav                   missing                           pak0
hq_tunnelstop.wav                   missing                           pak0
hq_walldest.wav                     missing                           pak0
hq_wallstop.wav                     missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


general
^^^^^^^


allies
++++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
hq_2minutes_a.wav                   missing                           pak0
hq_2minutes_b.wav                   missing                           pak0
hq_5minutes_a.wav                   missing                           pak0
hq_5minutes_b.wav                   missing                           pak0
hq_30seconds_a.wav                  missing                           pak0
hq_30seconds_b.wav                  missing                           pak0
hq_airabort_a.wav                   missing                           pak0
hq_airabort_b.wav                   missing                           pak0
hq_airdenied_a.wav                  missing                           pak0
hq_airdenied_b.wav                  missing                           pak0
hq_airstrike_a.wav                  missing                           pak0
hq_airstrike_b.wav                  missing                           pak0
hq_artabort_a.wav                   missing                           pak0
hq_artabort_b.wav                   missing                           pak0
hq_artdenied_a.wav                  missing                           pak0
hq_artdenied_b.wav                  missing                           pak0
hq_artillery_a.wav                  missing                           pak0
hq_artillery_b.wav                  missing                           pak0
hq_conconst_a.wav                   missing                           pak0
hq_conconst_b.wav                   missing                           pak0
hq_condest_a.wav                    missing                           pak0
hq_condest_b.wav                    missing                           pak0
hq_confail.wav                      missing                           pak0
hq_cpconst2.wav                     missing                           pak0
hq_cpconst_a.wav                    missing                           pak0
hq_cpconst_b.wav                    missing                           pak0
hq_cpcon_a.wav                      missing                           pak0
hq_cpcon_b.wav                      missing                           pak0
hq_cpdam.wav                        missing                           pak0
hq_cprep.wav                        missing                           pak0
hq_dyndefused2_a.wav                missing                           pak0
hq_dyndefused2_b.wav                missing                           pak0
hq_dyndefused_a.wav                 missing                           pak0
hq_dyndefused_b.wav                 missing                           pak0
hq_dynplanted2_a.wav                missing                           pak0
hq_dynplanted2_b.wav                missing                           pak0
hq_dynplanted_a.wav                 missing                           pak0
hq_dynplanted_b.wav                 missing                           pak0
hq_minesspot.wav                    missing                           pak0
hq_needcos_a.wav                    missing                           pak0
hq_needcos_b.wav                    missing                           pak0
hq_needeng_a.wav                    missing                           pak0
hq_needeng_b.wav                    missing                           pak0
hq_needfos_a.wav                    missing                           pak0
hq_needfos_b.wav                    missing                           pak0
hq_needmedic_a.wav                  missing                           pak0
hq_needmedic_b.wav                  missing                           pak0
hq_needsoldier_a.wav                missing                           pak0
hq_needsoldier_b.wav                missing                           pak0
hq_objcap.wav                       missing                           pak0
hq_objdest.wav                      missing                           pak0
hq_objlost.wav                      missing                           pak0
hq_objsec.wav                       missing                           pak0
hq_objtaken.wav                     missing                           pak0
hq_promocol.wav                     missing                           pak0
hq_promocpl.wav                     missing                           pak0
hq_promocpt.wav                     missing                           pak0
hq_promogen.wav                     missing                           pak0
hq_promogenbrig.wav                 missing                           pak0
hq_promogenlt.wav                   missing                           pak0
hq_promolt.wav                      missing                           pak0
hq_promomaj.wav                     missing                           pak0
hq_promopfc.wav                     missing                           pak0
hq_promosgt.wav                     missing                           pak0
hq_tankdam_a.wav                    missing                           pak0
hq_tankdam_b.wav                    missing                           pak0
hq_tankesc_a.wav                    missing                           pak0
hq_tankesc_b.wav                    missing                           pak0
hq_tankrep_a.wav                    missing                           pak0
hq_tankrep_b.wav                    missing                           pak0
hq_truckdam_a.wav                   missing                           pak0
hq_truckdam_b.wav                   missing                           pak0
hq_truckesc_a.wav                   missing                           pak0
hq_truckesc_b.wav                   missing                           pak0
hq_truckrep_a.wav                   missing                           pak0
hq_truckrep_b.wav                   missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


axis
++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
hq_2minutes.wav                     missing                           pak0
hq_5minutes.wav                     missing                           pak0
hq_30seconds.wav                    missing                           pak0
hq_airabort.wav                     missing                           pak0
hq_airdenied.wav                    missing                           pak0
hq_airstrike_a.wav                  missing                           pak0
hq_airstrike_b.wav                  missing                           pak0
hq_artabort.wav                     missing                           pak0
hq_artdenied_a.wav                  missing                           pak0
hq_artdenied_b.wav                  missing                           pak0
hq_artillery_a.wav                  missing                           pak0
hq_artillery_b.wav                  missing                           pak0
hq_conconst_a.wav                   missing                           pak0
hq_conconst_b.wav                   missing                           pak0
hq_condest_a.wav                    missing                           pak0
hq_confail_b.wav                    missing                           pak0
hq_cpconst2_a.wav                   missing                           pak0
hq_cpconst2_b.wav                   missing                           pak0
hq_cpconst_a.wav                    missing                           pak0
hq_cpconst_b.wav                    missing                           pak0
hq_cpcon_a.wav                      missing                           pak0
hq_cpcon_b.wav                      missing                           pak0
hq_cpdam.wav                        missing                           pak0
hq_cprep.wav                        missing                           pak0
hq_dyndefused2_a.wav                missing                           pak0
hq_dyndefused2_b.wav                missing                           pak0
hq_dyndefused_a.wav                 missing                           pak0
hq_dyndefused_b.wav                 missing                           pak0
hq_dynplanted2_a.wav                missing                           pak0
hq_dynplanted2_b.wav                missing                           pak0
hq_dynplanted_a.wav                 missing                           pak0
hq_dynplanted_b.wav                 missing                           pak0
hq_minesspot.wav                    missing                           pak0
hq_needcos_a.wav                    missing                           pak0
hq_needcos_b.wav                    missing                           pak0
hq_needeng_a.wav                    missing                           pak0
hq_needeng_b.wav                    missing                           pak0
hq_needfos_a.wav                    missing                           pak0
hq_needfos_b.wav                    missing                           pak0
hq_needmedic_a.wav                  missing                           pak0
hq_needmedic_b.wav                  missing                           pak0
hq_needsoldier_a.wav                missing                           pak0
hq_needsoldier_b.wav                missing                           pak0
hq_objcap.wav                       missing                           pak0
hq_objdest.wav                      missing                           pak0
hq_objlost.wav                      missing                           pak0
hq_objsec.wav                       missing                           pak0
hq_objtaken.wav                     missing                           pak0
hq_promocol.wav                     missing                           pak0
hq_promocpl.wav                     missing                           pak0
hq_promocpt.wav                     missing                           pak0
hq_promogen.wav                     missing                           pak0
hq_promogenlt.wav                   missing                           pak0
hq_promogenmaj.wav                  missing                           pak0
hq_promolt.wav                      missing                           pak0
hq_promomaj.wav                     missing                           pak0
hq_promopfc.wav                     missing                           pak0
hq_promosgt.wav                     missing                           pak0
hq_tankdam_a.wav                    missing                           pak0
hq_tankdam_b.wav                    missing                           pak0
hq_tankrep_a.wav                    missing                           pak0
hq_tankrep_b.wav                    missing                           pak0
hq_tankstop_a.wav                   missing                           pak0
hq_tankstop_b.wav                   missing                           pak0
hq_truckdam_a.wav                   missing                           pak0
hq_truckdam_b.wav                   missing                           pak0
hq_truckrep_a.wav                   missing                           pak0
hq_truckrep_b.wav                   missing                           pak0
hq_truckstop_a.wav                  missing                           pak0
hq_truckstop_b.wav                  missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


goldrush
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
news_goldrush.wav                   missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


allies
++++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
hq_bankyard.wav                     missing                           pak0
hq_gold1lost.wav                    missing                           pak0
hq_gold1ret.wav                     missing                           pak0
hq_gold1sec.wav                     missing                           pak0
hq_gold1taken.wav                   missing                           pak0
hq_gold2lost.wav                    missing                           pak0
hq_gold2ret.wav                     missing                           pak0
hq_gold2sec.wav                     missing                           pak0
hq_gold2taken.wav                   missing                           pak0
hq_goldget.wav                      missing                           pak0
hq_tankbank.wav                     missing                           pak0
hq_tankbar1.wav                     missing                           pak0
hq_tankbar2.wav                     missing                           pak0
hq_tankbardest.wav                  missing                           pak0
hq_tankbardyn.wav                   missing                           pak0
hq_tankbarsdyn.wav                  missing                           pak0
hq_tanksteal.wav                    missing                           pak0
hq_tankstolen.wav                   missing                           pak0
hq_truckbar1.wav                    missing                           pak0
hq_truckbar2.wav                    missing                           pak0
hq_truckbardest.wav                 missing                           pak0
hq_truckbardyn.wav                  missing                           pak0
hq_truckbarsdyn.wav                 missing                           pak0
hq_trucksteal.wav                   missing                           pak0
hq_truckstolen.wav                  missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


axis
++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
hq_bankbroken.wav                   missing                           pak0
hq_bankyard.wav                     missing                           pak0
hq_gold1lost.wav                    missing                           pak0
hq_gold1ret.wav                     missing                           pak0
hq_gold1sec.wav                     missing                           pak0
hq_gold1taken.wav                   missing                           pak0
hq_gold2lost.wav                    missing                           pak0
hq_gold2ret.wav                     missing                           pak0
hq_gold2sec.wav                     missing                           pak0
hq_gold2taken.wav                   missing                           pak0
hq_golddef.wav                      missing                           pak0
hq_tankbar1.wav                     missing                           pak0
hq_tankbar2.wav                     missing                           pak0
hq_tankbarcon.wav                   missing                           pak0
hq_tankbarconst.wav                 missing                           pak0
hq_tankbardest.wav                  missing                           pak0
hq_tankbarscon.wav                  missing                           pak0
hq_tankstolen.wav                   missing                           pak0
hq_truckbar1.wav                    missing                           pak0
hq_truckbar2.wav                    missing                           pak0
hq_truckbarcon.wav                  missing                           pak0
hq_truckbarconst.wav                missing                           pak0
hq_truckbardest.wav                 missing                           pak0
hq_truckbarscon.wav                 missing                           pak0
hq_trucksteal.wav                   missing                           pak0
hq_truckstolen.wav                  missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


oasis
^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
news_oasis.wav                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


allies
++++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
hq_cavesdrain.wav                   missing                           pak0
hq_cavesflood.wav                   missing                           pak0
hq_citycap.wav                      missing                           pak0
hq_citycapd.wav                     missing                           pak0
hq_cityrecl.wav                     missing                           pak0
hq_paknorthdest.wav                 missing                           pak0
hq_paknorthdyn.wav                  missing                           pak0
hq_paksdyn.wav                      missing                           pak0
hq_paksouthdest.wav                 missing                           pak0
hq_paksouthdyn.wav                  missing                           pak0
hq_pumpdis.wav                      missing                           pak0
hq_pumprep.wav                      missing                           pak0
hq_pumprepd.wav                     missing                           pak0
hq_pumpscon.wav                     missing                           pak0
hq_pumpsrep.wav                     missing                           pak0
hq_walldest.wav                     missing                           pak0
hq_walldyn.wav                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


axis
++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
hq_cavesdrain.wav                   missing                           pak0
hq_cavesflood.wav                   missing                           pak0
hq_citydef.wav                      missing                           pak0
hq_citylost.wav                     missing                           pak0
hq_cityrecl.wav                     missing                           pak0
hq_paknorthdef.wav                  missing                           pak0
hq_paknorthdest.wav                 missing                           pak0
hq_paksdef.wav                      missing                           pak0
hq_paksouthdef.wav                  missing                           pak0
hq_paksouthdest.wav                 missing                           pak0
hq_pumpdis.wav                      missing                           pak0
hq_pumprep.wav                      missing                           pak0
hq_pumpsstop.wav                    missing                           pak0
hq_pumpstop.wav                     missing                           pak0
hq_walldef.wav                      missing                           pak0
hq_walldest.wav                     missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


radar
^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
news_radar.wav                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


allies
++++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
hq_bunkercap.wav                    missing                           pak0
hq_bunkercapd.wav                   missing                           pak0
hq_bunkerrecl.wav                   missing                           pak0
hq_entrance1dest.wav                missing                           pak0
hq_entrance1dyn.wav                 missing                           pak0
hq_entrance2dest.wav                missing                           pak0
hq_entrance2dyn.wav                 missing                           pak0
hq_entrancesdyn.wav                 missing                           pak0
hq_radarelost.wav                   missing                           pak0
hq_radareret.wav                    missing                           pak0
hq_radaresec.wav                    missing                           pak0
hq_radaresteal.wav                  missing                           pak0
hq_radaretaken.wav                  missing                           pak0
hq_radarssteal.wav                  missing                           pak0
hq_radarwlost.wav                   missing                           pak0
hq_radarwret.wav                    missing                           pak0
hq_radarwsec.wav                    missing                           pak0
hq_radarwsteal.wav                  missing                           pak0
hq_radarwtaken.wav                  missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


axis
++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
hq_bunkercapd.wav                   missing                           pak0
hq_bunkerrecl.wav                   missing                           pak0
hq_bunkerstop.wav                   missing                           pak0
hq_entrance1def.wav                 missing                           pak0
hq_entrance1dest.wav                missing                           pak0
hq_entrance1stop.wav                missing                           pak0
hq_entrance2def.wav                 missing                           pak0
hq_entrance2dest.wav                missing                           pak0
hq_entrance2stop.wav                missing                           pak0
hq_entrancesdef.wav                 missing                           pak0
hq_radaredef.wav                    missing                           pak0
hq_radarelost.wav                   missing                           pak0
hq_radareret.wav                    missing                           pak0
hq_radaresec.wav                    missing                           pak0
hq_radaretaken.wav                  missing                           pak0
hq_radarsdef.wav                    missing                           pak0
hq_radarwdef.wav                    missing                           pak0
hq_radarwlost.wav                   missing                           pak0
hq_radarwret.wav                    missing                           pak0
hq_radarwsec.wav                    missing                           pak0
hq_radarwtaken.wav                  missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


railgun
^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
news_railgun.wav                    missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


allies
++++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
hq_depotcap.wav                     missing                           pak0
hq_depotcapd.wav                    missing                           pak0
hq_depotrecl.wav                    missing                           pak0
hq_gunctrldest.wav                  missing                           pak0
hq_gunctrldyn.wav                   missing                           pak0
hq_gunctrlrep.wav                   missing                           pak0
hq_gunfirestop.wav                  missing                           pak0
hq_switchlower.wav                  missing                           pak0
hq_switchlowered.wav                missing                           pak0
hq_switchraise.wav                  missing                           pak0
hq_switchraised.wav                 missing                           pak0
hq_tug1depot.wav                    missing                           pak0
hq_tug1loaded.wav                   missing                           pak0
hq_tug1north.wav                    missing                           pak0
hq_tug2loaded.wav                   missing                           pak0
hq_tug2railgun.wav                  missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


axis
++++

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
hq_depotcap.wav                     missing                           pak0
hq_depotcapd.wav                    missing                           pak0
hq_depotrecl.wav                    missing                           pak0
hq_gunctrlcon.wav                   missing                           pak0
hq_gunctrldef.wav                   missing                           pak0
hq_gunctrldest.wav                  missing                           pak0
hq_gunfire.wav                      missing                           pak0
hq_gunloaded.wav                    missing                           pak0
hq_switchlower.wav                  missing                           pak0
hq_switchraise.wav                  missing                           pak0
hq_switchraised.wav                 missing                           pak0
hq_tug1allies.wav                   missing                           pak0
hq_tug1depot.wav                    missing                           pak0
hq_tug1loaded.wav                   missing                           pak0
hq_tug1north.wav                    missing                           pak0
hq_tug2allies.wav                   missing                           pak0
hq_tug2loaded.wav                   missing                           pak0
hq_tug2railgun.wav                  missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


weapons
-------


airstrike
^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
airstrike_expl_1.wav                missing                           pak0
airstrike_expl_2.wav                missing                           pak0
airstrike_expl_3.wav                missing                           pak0
airstrike_expl_far.wav              missing                           pak0
airstrike_plane.wav                 missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


artillery
^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
artillery_expl_1.wav                missing                           pak0
artillery_expl_2.wav                missing                           pak0
artillery_expl_3.wav                missing                           pak0
artillery_expl_far.wav              missing                           pak0
artillery_fly_1.wav                 missing                           pak0
artillery_fly_2.wav                 missing                           pak0
artillery_fly_3.wav                 missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


browning
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
browning_far.wav                    missing                           pak0
browning_fire.wav                   missing                           pak0
browning_heat.wav                   missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


colt
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
colt_far.wav                        missing                           pak0
colt_fire.wav                       missing                           pak0
colt_reload.wav                     missing                           pak0
colt_reload_akimbo.wav              missing                           pak0
colt_reload_fast.wav                missing                           pak0
colt_silence.wav                    missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


dynamite
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
dynamite_bounce.wav                 missing                           pak0
dynamite_expl.wav                   missing                           pak0
dynamite_expl_far.wav               missing                           pak0
dynamite_timer.wav                  missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


fg42
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
fg42_far.wav                        missing                           pak0
fg42_fire.wav                       missing                           pak0
fg42_reload.wav                     missing                           pak0
fg42_reload_fast.wav                missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


flamethrower
^^^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
flame_burn.wav                      missing                           pak0
flame_fire.wav                      missing                           pak0
flame_pilot.wav                     missing                           pak0
flame_up.wav                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


garand
^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
m1_far.wav                          missing                           pak0
m1_fire.wav                         missing                           pak0
m1_fire_grenade.wav                 missing                           pak0
m1_fire_last.wav                    missing                           pak0
m1_fire_silence.wav                 missing                           pak0
m1_fire_silence_last.wav            missing                           pak0
m1_grenade_fly.wav                  missing                           pak0
m1_grenade_off.wav                  missing                           pak0
m1_grenade_on.wav                   missing                           pak0
m1_reload.wav                       missing                           pak0
m1_reload_grenade.wav               missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


grenade
^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
bounce_hard1.wav                    missing                           pak0
bounce_hard2.wav                    missing                           pak0
bounce_metal1.wav                   missing                           pak0
bounce_metal2.wav                   missing                           pak0
bounce_soft1.wav                    missing                           pak0
bounce_soft2.wav                    missing                           pak0
bounce_wood1.wav                    missing                           pak0
bounce_wood2.wav                    missing                           pak0
gren_expl.wav                       missing                           pak0
gren_expl_far.wav                   missing                           pak0
gren_expl_water.wav                 missing                           pak0
gren_smoke.wav                      missing                           pak0
gren_throw.wav                      missing                           pak0
gren_timer1.wav                     missing                           pak0
gren_timer2.wav                     missing                           pak0
gren_timer3.wav                     missing                           pak0
gren_timer4.wav                     missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


impact
^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
flesh1.wav                          missing                           pak0
flesh2.wav                          missing                           pak0
flesh3.wav                          missing                           pak0
flesh4.wav                          missing                           pak0
flesh5.wav                          missing                           pak0
glass1.wav                          missing                           pak0
glass2.wav                          missing                           pak0
glass3.wav                          missing                           pak0
glass4.wav                          missing                           pak0
glass5.wav                          missing                           pak0
metal1.wav                          missing                           pak0
metal2.wav                          missing                           pak0
metal3.wav                          missing                           pak0
metal4.wav                          missing                           pak0
metal5.wav                          missing                           pak0
stone1.wav                          missing                           pak0
stone2.wav                          missing                           pak0
stone3.wav                          missing                           pak0
stone4.wav                          missing                           pak0
stone5.wav                          missing                           pak0
water1.wav                          missing                           pak0
water2.wav                          missing                           pak0
water3.wav                          missing                           pak0
water4.wav                          missing                           pak0
water5.wav                          missing                           pak0
wood1.wav                           missing                           pak0
wood2.wav                           missing                           pak0
wood3.wav                           missing                           pak0
wood4.wav                           missing                           pak0
wood5.wav                           missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


k43
^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
k43_far.wav                         missing                           pak0
k43_fire.wav                        missing                           pak0
k43_fire_grenade.wav                missing                           pak0
k43_fire_silence.wav                missing                           pak0
k43_grenade_fly.wav                 missing                           pak0
k43_grenade_off.wav                 missing                           pak0
k43_grenade_on.wav                  missing                           pak0
k43_reload.wav                      missing                           pak0
k43_reload_grenade.wav              missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


knife
^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
knife_hit1.wav                      missing                           pak0
knife_hit2.wav                      missing                           pak0
knife_hit3.wav                      missing                           pak0
knife_hit4.wav                      missing                           pak0
knife_hitwall1.wav                  missing                           pak0
knife_slash1.wav                    missing                           pak0
knife_slash2.wav                    missing                           pak0
knife_slash3.wav                    missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


landmine
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
mine_bounce.wav                     missing                           pak0
mine_expl.wav                       missing                           pak0
mine_expl_far.wav                   missing                           pak0
mine_on.wav                         missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


luger
^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
luger_far.wav                       missing                           pak0
luger_fire.wav                      missing                           pak0
luger_reload.wav                    missing                           pak0
luger_reload_akimbo.wav             missing                           pak0
luger_reload_fast.wav               missing                           pak0
luger_silence.wav                   missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


mg42
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
mg42_far.wav                        missing                           pak0
mg42_fire.wav                       missing                           pak0
mg42_heat.wav                       missing                           pak0
mg42_reload.wav                     missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


misc
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
change.wav                          missing                           pak0
fire_dry.wav                        missing                           pak0
fire_water.wav                      missing                           pak0
shell_metal1.wav                    missing                           pak0
shell_metal2.wav                    missing                           pak0
shell_metal3.wav                    missing                           pak0
shell_soft1.wav                     missing                           pak0
shell_soft2.wav                     missing                           pak0
shell_soft3.wav                     missing                           pak0
shell_stone1.wav                    missing                           pak0
shell_stone2.wav                    missing                           pak0
shell_stone3.wav                    missing                           pak0
shell_wood1.wav                     missing                           pak0
shell_wood2.wav                     missing                           pak0
shell_wood3.wav                     missing                           pak0
silence_off.wav                     missing                           pak0
silence_on.wav                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


mortar
^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
mortar_expl.wav                     missing                           pak0
mortar_expl1.wav                    missing                           pak0
mortar_expl2.wav                    missing                           pak0
mortar_expl3.wav                    missing                           pak0
mortar_expl_far.wav                 missing                           pak0
mortar_fire.wav                     missing                           pak0
mortar_fly.wav                      missing                           pak0
mortar_off.wav                      missing                           pak0
mortar_on.wav                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


mp40
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
mp40_far.wav                        missing                           pak0
mp40_fire.wav                       missing                           pak0
mp40_reload.wav                     missing                           pak0
mp40_reload_fast.wav                missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


rocket
^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
rocket_charge.wav                   missing                           pak0
rocket_expl.wav                     missing                           pak0
rocket_expl_far.wav                 missing                           pak0
rocket_fire.wav                     missing                           pak0
rocket_fly.wav                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


satchel
^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
remote_fire.wav                     missing                           pak0
remote_hum.wav                      missing                           pak0
satchel_bounce.wav                  missing                           pak0
satchel_expl.wav                    missing                           pak0
satchel_expl_far.wav                missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


sten
^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
sten_fire.wav                       missing                           pak0
sten_heat.wav                       missing                           pak0
sten_reload.wav                     missing                           pak0
sten_reload_fast.wav                missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


thompson
^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
thompson_far.wav                    missing                           pak0
thompson_fire.wav                   missing                           pak0
thompson_reload.wav                 missing                           pak0
thompson_reload_fast.wav            missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


world
-----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
alarm_01.wav                        missing                           pak0
alarm_02.wav                        missing                           pak0
beeper.wav                          missing                           pak0
boardbreak.wav                      missing                           pak0
bubbles.wav                         missing                           pak0
build.wav                           missing                           pak0
chaircreak.wav                      missing                           pak0
crickets_01.wav                     missing                           pak0
crickets_02.wav                     missing                           pak0
debris.wav                          missing                           pak0
debris1.wav                         missing                           pak0
debris2.wav                         missing                           pak0
debris3.wav                         missing                           pak0
desert.wav                          missing                           pak0
dog_01.wav                          missing                           pak0
dog_02.wav                          missing                           pak0
dripping_01.wav                     missing                           pak0
dripping_02.wav                     missing                           pak0
fan_fast.wav                        missing                           pak0
fan_med.wav                         missing                           pak0
fan_slow.wav                        missing                           pak0
fire_01.wav                         missing                           pak0
fire_02.wav                         missing                           pak0
flag.wav                            missing                           pak0
flap.wav                            missing                           pak0
glassbreak1.wav                     missing                           pak0
glassbreak2.wav                     missing                           pak0
glassbreak3.wav                     missing                           pak0
hum.wav                             missing                           pak0
icecrack.wav                        missing                           pak0
leaves.wav                          missing                           pak0
lights.wav                          missing                           pak0
machine_01.wav                      missing                           pak0
machine_02.wav                      missing                           pak0
machine_03.wav                      missing                           pak0
metalbreak.wav                      missing                           pak0
owl.wav                             missing                           pak0
parrot.wav                          missing                           pak0
pigeon.wav                          missing                           pak0
radio_allies.wav                    missing                           pak0
radio_axis.wav                      missing                           pak0
radio_static_01.wav                 missing                           pak0
radio_static_02.wav                 missing                           pak0
rain_hard.wav                       missing                           pak0
rain_indoor.wav                     missing                           pak0
rain_soft.wav                       missing                           pak0
rain_tent.wav                       missing                           pak0
rain_trickle.wav                    missing                           pak0
rooster.wav                         missing                           pak0
steam_01.wav                        missing                           pak0
steam_02.wav                        missing                           pak0
steam_03.wav                        missing                           pak0
thunder_01.wav                      missing                           pak0
thunder_02.wav                      missing                           pak0
thunder_03.wav                      missing                           pak0
thunder_04.wav                      missing                           pak0
thunder_05.wav                      missing                           pak0
transformer.wav                     missing                           pak0
war.wav                             missing                           pak0
waterpump.wav                       missing                           pak0
water_01.wav                        missing                           pak0
water_02.wav                        missing                           pak0
water_03.wav                        missing                           pak0
wind_city.wav                       missing                           pak0
wind_forest.wav                     missing                           pak0
wind_hall.wav                       missing                           pak0
wind_mountain.wav                   missing                           pak0
wind_ocean.wav                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


sprites
=======

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
active_uniform_allied.tga           missing                           pak0
active_uniform_axis.tga             missing                           pak0
attack.tga                          missing                           pak0
balloon4.tga                        missing                           pak0
bloodCloud.tga                      missing                           pak0
blood_dot1.tga                      missing                           pak0
blood_dot2.tga                      missing                           pak0
blood_dot3.tga                      missing                           pak0
blood_dot4.tga                      missing                           pak0
blood_dot5.tga                      missing                           pak0
bubble.tga                          missing                           pak0
buddy.tga                           missing                           pak0
bullettrail.tga                     missing                           pak0
construct.tga                       missing                           pak0
defend.tga                          missing                           pak0
destroy.tga                         missing                           pak0
fire_sm_a.tga                       missing                           pak0
fire_sm_b.tga                       missing                           pak0
fire_sm_c.tga                       missing                           pak0
fire_sm_d.tga                       missing                           pak0
fire_sm_e.tga                       missing                           pak0
fire_sm_f.tga                       missing                           pak0
fthrow_bluestream1.jpg              missing                           pak0
fthrow_firestream2.jpg              missing                           pak0
icon_shield.tga                     missing                           pak0
inferno_blue.tga                    missing                           pak0
landmine_allied.tga                 missing                           pak0
landmine_axis.tga                   missing                           pak0
medicrevive.tga                     missing                           pak0
objective.tga                       missing                           pak0
oil_PARTICLE.tga                    missing                           pak0
regroup.tga                         missing                           pak0
shadow_foot.jpg                     missing                           pak0
shadow_torso.tga                    missing                           pak0
smokepuff.tga                       missing                           pak0
smoketrail2.tga                     missing                           pak0
spark.tga                           missing                           pak0
splashalpha.tga                     missing                           pak0
viewflash_red.jpg                   missing                           pak0
voiceammo.tga                       missing                           pak0
voicechat.tga                       missing                           pak0
voicemedic.tga                      missing                           pak0
wake.tga                            missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


clnfire
-------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
spr000.tga                          missing                           pak0
spr001.tga                          missing                           pak0
spr002.tga                          missing                           pak0
spr003.tga                          missing                           pak0
spr004.tga                          missing                           pak0
spr005.tga                          missing                           pak0
spr006.tga                          missing                           pak0
spr007.tga                          missing                           pak0
spr008.tga                          missing                           pak0
spr009.tga                          missing                           pak0
spr010.tga                          missing                           pak0
spr011.tga                          missing                           pak0
spr012.tga                          missing                           pak0
spr013.tga                          missing                           pak0
spr014.tga                          missing                           pak0
spr015.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


explode1
--------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
spr000.tga                          missing                           pak0
spr001.tga                          missing                           pak0
spr002.tga                          missing                           pak0
spr003.tga                          missing                           pak0
spr004.tga                          missing                           pak0
spr005.tga                          missing                           pak0
spr006.tga                          missing                           pak0
spr007.tga                          missing                           pak0
spr008.tga                          missing                           pak0
spr009.tga                          missing                           pak0
spr010.tga                          missing                           pak0
spr011.tga                          missing                           pak0
spr012.tga                          missing                           pak0
spr013.tga                          missing                           pak0
spr014.tga                          missing                           pak0
spr015.tga                          missing                           pak0
spr016.tga                          missing                           pak0
spr017.tga                          missing                           pak0
spr018.tga                          missing                           pak0
spr019.tga                          missing                           pak0
spr020.tga                          missing                           pak0
spr021.tga                          missing                           pak0
spr022.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


nozzle
------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
noz001.tga                          missing                           pak0
noz002.tga                          missing                           pak0
noz003.tga                          missing                           pak0
noz004.tga                          missing                           pak0
noz005.tga                          missing                           pak0
noz006.tga                          missing                           pak0
noz007.tga                          missing                           pak0
noz008.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


twiltb2
-------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
spr000.tga                          missing                           pak0
spr001.tga                          missing                           pak0
spr002.tga                          missing                           pak0
spr003.tga                          missing                           pak0
spr004.tga                          missing                           pak0
spr005.tga                          missing                           pak0
spr006.tga                          missing                           pak0
spr007.tga                          missing                           pak0
spr008.tga                          missing                           pak0
spr009.tga                          missing                           pak0
spr010.tga                          missing                           pak0
spr011.tga                          missing                           pak0
spr012.tga                          missing                           pak0
spr013.tga                          missing                           pak0
spr014.tga                          missing                           pak0
spr015.tga                          missing                           pak0
spr016.tga                          missing                           pak0
spr017.tga                          missing                           pak0
spr018.tga                          missing                           pak0
spr019.tga                          missing                           pak0
spr020.tga                          missing                           pak0
spr021.tga                          missing                           pak0
spr022.tga                          missing                           pak0
spr023.tga                          missing                           pak0
spr024.tga                          missing                           pak0
spr025.tga                          missing                           pak0
spr026.tga                          missing                           pak0
spr027.tga                          missing                           pak0
spr028.tga                          missing                           pak0
spr029.tga                          missing                           pak0
spr030.tga                          missing                           pak0
spr031.tga                          missing                           pak0
spr032.tga                          missing                           pak0
spr033.tga                          missing                           pak0
spr034.tga                          missing                           pak0
spr035.tga                          missing                           pak0
spr036.tga                          missing                           pak0
spr037.tga                          missing                           pak0
spr038.tga                          missing                           pak0
spr039.tga                          missing                           pak0
spr040.tga                          missing                           pak0
spr041.tga                          missing                           pak0
spr042.tga                          missing                           pak0
spr043.tga                          missing                           pak0
spr044.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


text
====


EnglishUSA
----------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
credit_id.txt                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


textures
========


alpha
-----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
barb_wire.tga                       missing                           pak0
bars_m01.tga                        missing                           pak0
bel_orn_m01.tga                     missing                           pak0
chateau_c06a.tga                    missing                           pak0
chateau_c07.tga                     missing                           pak0
chateau_c08.tga                     missing                           pak0
chateau_c11.tga                     missing                           pak0
fence_c10.tga                       missing                           pak0
fence_c11.tga                       missing                           pak0
fence_c14.tga                       missing                           pak0
fence_m01.tga                       missing                           pak0
fence_m06.tga                       missing                           pak0
fence_m06b.tga                      missing                           pak0
ladder.tga                          missing                           pak0
mesh_c02.tga                        missing                           pak0
mesh_c03.tga                        missing                           pak0
truss_m03.tga                       missing                           pak0
truss_m06.tga                       missing                           pak0
truss_m06a.tga                      missing                           pak0
truss_m06r.tga                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


assault
-------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
atool_m02.jpg                       missing                           pak0
atruss_m06a.tga                     missing                           pak0
awall_m01.jpg                       missing                           pak0
machine_c01b.jpg                    missing                           pak0
machine_c05b.jpg                    missing                           pak0
metal_c06.jpg                       missing                           pak0
metal_c07a.jpg                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


assault_rock
------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
concrete_m02.jpg                    missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


awf
---

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
awf_w_m10.jpg                       missing                           pak0
awf_w_m11.tga                       missing                           pak0
floor_m4.jpg                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


awf_props
---------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
tool_m01.jpg                        missing                           pak0
tool_m02.jpg                        missing                           pak0
tool_m06.jpg                        missing                           pak0
tool_m07.tga                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


battery_wall
------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
metal_trim1.tga                     missing                           pak0
wall01_mid.tga                      missing                           pak0
wall01_top.tga                      missing                           pak0
wall01_trench.tga                   missing                           pak0
wall02_bot.jpg                      missing                           pak0
wall02_mid.jpg                      missing                           pak0
wall02_top.jpg                      missing                           pak0
wall03_bot.tga                      missing                           pak0
wall03_mid.tga                      missing                           pak0
wall03_top.tga                      missing                           pak0
wall03_trench.tga                   missing                           pak0
wall04_mid.tga                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


broken_castle
-------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
wall_c03d.jpg                       missing                           pak0
wall_c04.jpg                        missing                           pak0
wall_c05.jpg                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


bunker_sd
---------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
concrete_c07bcmp_sand.tga           missing                           pak0
girder02.tga                        missing                           pak0
girder03.tga                        missing                           pak0
int_wall01.tga                      missing                           pak0
int_wall01_rusty.tga                missing                           pak0
int_wall01_white.tga                missing                           pak0
int_wall07.tga                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


castle_door
-----------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
door_c17.jpg                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


castle_wall
-----------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
castle_c09_2.jpg                    missing                           pak0
castle_c17.jpg                      missing                           pak0
castle_c31_a.jpg                    missing                           pak0
castle_m03a_step.jpg                missing                           pak0
castle_m03_step_grave_03.jpg        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


castle_wood
-----------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
cwood_c10.jpg                       missing                           pak0
cwood_mo2s1.tga                     missing                           pak0
cwood_mo6.jpg                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


cathedrale_wall
---------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
cathedrale_c09.jpg                  missing                           pak0
cathedrale_c13.jpg                  missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


chat
----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
bedlinenpillow_c02.jpg              missing                           pak0
bedlinen_c02.jpg                    missing                           pak0
bedlinen_c04.jpg                    missing                           pak0
book_c02.jpg                        missing                           pak0
book_c05.jpg                        missing                           pak0
carpet_c03.jpg                      missing                           pak0
desk1.jpg                           missing                           pak0
picture_05.jpg                      missing                           pak0
wd_sr_va7.jpg                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


chateau
-------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
bricktrim_c06.jpg                   missing                           pak0
desk_c04.jpg                        missing                           pak0
door_c01.jpg                        missing                           pak0
floor_c10.jpg                       missing                           pak0
floor_c10a.jpg                      missing                           pak0
pillar_temp_rf.jpg                  missing                           pak0
trim_c09.jpg                        missing                           pak0
walltest_c04.jpg                    missing                           pak0
walltest_c07a.jpg                   missing                           pak0
wood_c05.jpg                        missing                           pak0
wood_test.jpg                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


chat_wood
---------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
chwood_c02.jpg                      missing                           pak0
chwood_c04.jpg                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


common
------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
dirtymirror.tga                     missing                           pak0
dirtymirror2.tga                    missing                           pak0
s_glass.tga                         missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


decals
------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
oil_slick.tga                       missing                           pak0
S_IDENT_REQUIRED_2R.tga             missing                           pak0
trim_m01.tga                        missing                           pak0
vent.jpg                            missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


desert_sd
---------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
floor_inside_1.tga                  missing                           pak0
grass_desert_flat.tga               missing                           pak0
grass_sand_flat.tga                 missing                           pak0
pavement_quad_sandy.tga             missing                           pak0
pavement_tris_sandy.tga             missing                           pak0
road_dirty_gravel.tga               missing                           pak0
rock_edged_smooth.tga               missing                           pak0
sand_dirt_medium.tga                missing                           pak0
sand_disturb_desert.tga             missing                           pak0
sand_gravels_bright.tga             missing                           pak0
sand_patchy.tga                     missing                           pak0
sand_wave_desert.tga                missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


detail_sd
---------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
sanddetail.tga                      missing                           pak0
snowdetail.tga                      missing                           pak0
snowdetail_heavy.tga                missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


doors
-----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
sanddetail.tga                      missing                           pak0
snowdetail.tga                      missing                           pak0
snowdetail_heavy.tga                missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


effects
-------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
envmap_gold.tga                     missing                           pak0
envmap_ice2.tga                     missing                           pak0
envmap_radar.tga                    missing                           pak0
envmap_slate.tga                    missing                           pak0
envmap_slate_90.tga                 missing                           pak0
tinfx.jpg                           missing                           pak0
wdfx4.jpg                           missing                           pak0
wdfx_W.jpg                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


egypt_door_sd
-------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
door_c05.jpg                        missing                           pak0
siwa_door2.jpg                      missing                           pak0
siwa_door3.tga                      missing                           pak0
siwa_door_axis.jpg                  missing                           pak0
siwa_door_neutral.jpg               missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


egypt_floor_sd
--------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
afloor_m02.jpg                      missing                           pak0
block-16sq.tga                      missing                           pak0
carpet_c02.jpg                      missing                           pak0
dirt_cracked_01.tga                 missing                           pak0
floor_c06.jpg                       missing                           pak0
marblefloor_c04.tga                 missing                           pak0
sandygrass_b.tga                    missing                           pak0
sandy_dirt_01.jpg                   missing                           pak0
siwa_rubble_1.jpg                   missing                           pak0
wood_c13.jpg                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


egypt_props_sd
--------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
siwa_book1.jpg                      missing                           pak0
siwa_book2.jpg                      missing                           pak0
siwa_canvas1.jpg                    missing                           pak0
siwa_carpet1.tga                    missing                           pak0
siwa_carpet2.tga                    missing                           pak0
siwa_carpet3.tga                    missing                           pak0
siwa_carpet4.tga                    missing                           pak0
siwa_carpet5.tga                    missing                           pak0
siwa_coran1.jpg                     missing                           pak0
siwa_coran2.jpg                     missing                           pak0
siwa_cushion1.jpg                   missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


egypt_trim_sd
-------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
banktrim01.tga                      missing                           pak0
banktrim03.tga                      missing                           pak0
banktrim04.tga                      missing                           pak0
ctrim_c01.jpg                       missing                           pak0
ctrim_c03.jpg                       missing                           pak0
trim_c03b.jpg                       missing                           pak0
trim_c03c.tga                       missing                           pak0
trim_c14.jpg                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


egypt_walls_sd
--------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
bankwall01.tga                      missing                           pak0
bigblock02.tga                      missing                           pak0
concrete_m03.jpg                    missing                           pak0
debri_m05.tga                       missing                           pak0
mat_wall1.jpg                       missing                           pak0
roughbrick01.tga                    missing                           pak0
roughbrick02.tga                    missing                           pak0
roughbrick03.tga                    missing                           pak0
roughbrick03a.tga                   missing                           pak0
roughedge01.tga                     missing                           pak0
stripedbrick01.tga                  missing                           pak0
stucco01.tga                        missing                           pak0
stucco01_decor01.tga                missing                           pak0
stucco02.tga                        missing                           pak0
stucco02_04blend.tga                missing                           pak0
stucco02_rough.tga                  missing                           pak0
stucco02_rough2.tga                 missing                           pak0
stucco03.tga                        missing                           pak0
stucco03b.tga                       missing                           pak0
stucco03_dark.tga                   missing                           pak0
stucco04.tga                        missing                           pak0
stucco07a.tga                       missing                           pak0
stucco07b.tga                       missing                           pak0
stucco07c.tga                       missing                           pak0
stucco07d.tga                       missing                           pak0
stucco07f.tga                       missing                           pak0
stucco07_trim03.tga                 missing                           pak0
stucco08a.jpg                       missing                           pak0
stucco08b.jpg                       missing                           pak0
stucco08c.jpg                       missing                           pak0
stucco08d.jpg                       missing                           pak0
stucco08e.jpg                       missing                           pak0
stucco09a.jpg                       missing                           pak0
stucco09b.jpg                       missing                           pak0
stucco09c.jpg                       missing                           pak0
stucco09d.jpg                       missing                           pak0
stucco09e.jpg                       missing                           pak0
stucco09f.jpg                       missing                           pak0
stucco09g.jpg                       missing                           pak0
stucco09h.jpg                       missing                           pak0
stucco09_bigexp.jpg                 missing                           pak0
white01.tga                         missing                           pak0
white01var01.tga                    missing                           pak0
white01var02.tga                    missing                           pak0
white01var03.tga                    missing                           pak0
wood_c05.jpg                        missing                           pak0
wood_c06.jpg                        missing                           pak0
wood_test.jpg                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


egypt_walls_xp
--------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
column_top_01.jpg                   missing                           pak0
large_block-4sq.jpg                 missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


egypt_windows_sd
----------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
siwa_windows2.jpg                   missing                           pak0
siwa_windows5.jpg                   missing                           pak0
siwa_windows6.jpg                   missing                           pak0
siwa_windows7.jpg                   missing                           pak0
siwa_windows8.jpg                   missing                           pak0
window02a.tga                       missing                           pak0
windowtrim01.tga                    missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


egypt_wood_sd
-------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
wood1a.tga                          missing                           pak0
wood1b.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


factory_sd
----------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
metal_wall1.tga                     missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


forest_sd
---------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
door_m01asml_axis.tga               missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


fueldump_sd
-----------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
door_m01asml.jpg                    missing                           pak0
door_m01asml_axis.tga               missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


graveyard
---------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
gy_ml03a.jpg                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


lights
------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
light_c01.blend.tga                 missing                           pak0
light_c01.tga                       missing                           pak0
light_c02.blend.tga                 missing                           pak0
light_c02.tga                       missing                           pak0
light_c04.blend.tga                 missing                           pak0
light_c04.tga                       missing                           pak0
light_m4.blend.tga                  missing                           pak0
light_m4.tga                        missing                           pak0
light_m5.blend.tga                  missing                           pak0
light_m5.tga                        missing                           pak0
light_m11.blend.tga                 missing                           pak0
light_m11.tga                       missing                           pak0
light_m15.blend.tga                 missing                           pak0
light_m15.tga                       missing                           pak0
light_m16.blend.tga                 missing                           pak0
light_m16.tga                       missing                           pak0
light_m21.blend.tga                 missing                           pak0
light_m21.tga                       missing                           pak0
light_m25r.tga                      missing                           pak0
light_xlight_02.tga                 missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


liquids_sd
----------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
puddle_specular.tga                 missing                           pak0
seawall_foam.tga                    missing                           pak0
seawall_ripple1.tga                 missing                           pak0
seawall_specular.tga                missing                           pak0
sea_bright_na.tga                   missing                           pak0
siwa_shimshim1.tga                  missing                           pak0
siwa_water.tga                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


metals_sd
---------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
detail_b.tga                        missing                           pak0
door_a.tga                          missing                           pak0
duct_a2.tga                         missing                           pak0
grate_a.tga                         missing                           pak0
grate_b.tga                         missing                           pak0
wall_b.tga                          missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


metal_misc
----------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
ametal_m01.jpg                      missing                           pak0
ametal_m02.jpg                      missing                           pak0
ametal_m03.jpg                      missing                           pak0
ametal_m03dm.tga                    missing                           pak0
ametal_m03man.jpg                   missing                           pak0
ametal_m03_bak.tga                  missing                           pak0
ametal_m04a.jpg                     missing                           pak0
ametal_m07a.jpg                     missing                           pak0
diamond_c_01.tga                    missing                           pak0
diamond_c_01b.jpg                   missing                           pak0
diamond_m03.jpg                     missing                           pak0
metal_m04dg.jpg                     missing                           pak0
metal_m04dr2.tga                    missing                           pak0
metal_m04g2-r.jpg                   missing                           pak0
metal_m04g2.jpg                     missing                           pak0
metal_m04r2.jpg                     missing                           pak0
metal_m06.jpg                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


miltary_door
------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
mdoor_c03.jpg                       missing                           pak0
mdoor_m01b.jpg                      missing                           pak0
miltarydr_m01.tga                   missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


miltary_wall
------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
brick_l_01.jpg                      missing                           pak0
concrete_c02.jpg                    missing                           pak0
concrete_c05.jpg                    missing                           pak0
concrete_c07bcmp.jpg                missing                           pak0
concrete_m01.jpg                    missing                           pak0
concrete_m02w.jpg                   missing                           pak0
concrete_m05c.jpg                   missing                           pak0
guardh_I03.jpg                      missing                           pak0
miltary_m04.jpg                     missing                           pak0
miltary_m06.jpg                     missing                           pak0
mroof_m01a.jpg                      missing                           pak0
window_m03.tga                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


occult
------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
menhir_c02a.jpg                     missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


props
-----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
bags_m01.jpg                        missing                           pak0
barrel_m01.tga                      missing                           pak0
barrel_m02.tga                      missing                           pak0
barrel_m02d.tga                     missing                           pak0
base_lamp.tga                       missing                           pak0
board_c01.tga                       missing                           pak0
board_c03.jpg                       missing                           pak0
board_cl02m.jpg                     missing                           pak0
box_c01.tga                         missing                           pak0
box_c02.tga                         missing                           pak0
box_c03.tga                         missing                           pak0
box_m01.jpg                         missing                           pak0
box_m02.tga                         missing                           pak0
box_m03.jpg                         missing                           pak0
box_m04.tga                         missing                           pak0
box_m04a.tga                        missing                           pak0
box_m04a_sd.tga                     missing                           pak0
box_m05.jpg                         missing                           pak0
box_m05a.jpg                        missing                           pak0
box_t_m01.tga                       missing                           pak0
box_t_m01a.jpg                      missing                           pak0
box_t_m04.jpg                       missing                           pak0
box_t_m04a.tga                      missing                           pak0
box_t_m04b.jpg                      missing                           pak0
cable_m01.jpg                       missing                           pak0
controlpanel_c02.jpg                missing                           pak0
controlpanel_c06.jpg                missing                           pak0
file_cab_m01.jpg                    missing                           pak0
fwindow1.tga                        missing                           pak0
hay.tga                             missing                           pak0
lockers_c01.jpg                     missing                           pak0
lockers_c02.jpg                     missing                           pak0
panelside_d01.jpg                   missing                           pak0
panel_d03.jpg                       missing                           pak0
panel_tram2.jpg                     missing                           pak0
panel_tram3.jpg                     missing                           pak0
rail_side_wils.jpg                  missing                           pak0
rope_m01.jpg                        missing                           pak0
sawblade.jpg                        missing                           pak0
sho_box_c01.tga                     missing                           pak0
sho_box_c02.jpg                     missing                           pak0
sho_box_c03.jpg                     missing                           pak0
sign_c06.jpg                        missing                           pak0
sign_c18.jpg                        missing                           pak0
sign_c26.jpg                        missing                           pak0
sign_c27.jpg                        missing                           pak0
sign_m2dm.jpg                       missing                           pak0
sub1.jpg                            missing                           pak0
train1.jpg                          missing                           pak0
train_m01.jpg                       missing                           pak0
train_m02.jpg                       missing                           pak0
train_m05.jpg                       missing                           pak0
train_m06.jpg                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


props_sd
--------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
basketsand.tga                      missing                           pak0
board_cl01m.jpg                     missing                           pak0
board_cl02m.jpg                     missing                           pak0
sign_radar.tga                      missing                           pak0
s_ammo01.tga                        missing                           pak0
s_casemate01.tga                    missing                           pak0
s_casemate02.tga                    missing                           pak0
s_generator01.tga                   missing                           pak0
s_gun01.tga                         missing                           pak0
trim_c01w.tga                       missing                           pak0
trim_c03w.tga                       missing                           pak0
trim_c10w.tga                       missing                           pak0
wires.tga                           missing                           pak0
wires01.tga                         missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


railgun_props
-------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
tug_side.tga                        missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


rubble
------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
burn_flr_m01.jpg                    missing                           pak0
debri_m01.jpg                       missing                           pak0
debri_m05.jpg                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


seawall_wall
------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
metal_trim1.tga                     missing                           pak0
wall02_mid.jpg                      missing                           pak0
wall03_mid.tga                      missing                           pak0
wall03_top.tga                      missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


sfx
---

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
beam_1.jpg                          missing                           pak0
construction.tga                    missing                           pak0
fan.tga                             missing                           pak0
flame1.tga                          missing                           pak0
flame2.tga                          missing                           pak0
flame3.tga                          missing                           pak0
flame4.tga                          missing                           pak0
flame5.tga                          missing                           pak0
flame6.tga                          missing                           pak0
flame7.tga                          missing                           pak0
flame8.tga                          missing                           pak0
flameball.tga                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


skies
-----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
fueldump_clouds.tga                 missing                           pak0
nightsky1.jpg                       missing                           pak0
=================================== ======== ============ =========== ======== ============= =============================


skies_sd
--------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
batterysunfog.tga
battery_clouds.tga
battery_mask_ydnar.tga
colditz_mask.tga
full_moon2.tga
goldrush_clouds.tga
goldrush_mask.tga
siwasun.tga
siwa_mask.tga
small_moon.tga
wurzburg_clouds.tga
wurzburg_fogmask.tga
ydnar_lightning.tga
=================================== ======== ============ =========== ======== ============= =============================


wurzburg_env
^^^^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
sky_bk.tga
sky_dn.tga
sky_ft.tga
sky_lf.tga
sky_rt.tga
sky_up.tga
=================================== ======== ============ =========== ======== ============= =============================


sleepy
------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
wall_c01.jpg
=================================== ======== ============ =========== ======== ============= =============================


snow
----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
alpha_ice2s.tga
s_bars_m01.tga
s_cashudder_c01.jpg
s_castle_c02.jpg
s_castle_c16d.jpg
s_castle_c46_on_grid.jpg
s_castle_m03a_step.jpg
s_castle_m03_step.jpg
s_cathedrale_c06.jpg
s_cathedrale_c24b.jpg
s_cwood_mo5c.jpg
s_diamond_c01a.jpg
s_dirt_m03i_2.jpg
s_dirt_m03i_alpha.tga
s_dirt_m03i_alphatree.tga
s_door_c10b.jpg
s_floor_c10_a2.jpg
s_floor_l_01.jpg
s_metal_m04dg2.jpg
s_roof_c04dm.jpg
s_town_c91.jpg
s_town_m_c01_trim.jpg
s_window_c05a.jpg
s_wood_c13a.jpg
=================================== ======== ============ =========== ======== ============= =============================


snow_sd
-------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
ametal_m03_snow.tga
ametal_m04a_snow.tga
ametal_m04a_snowfade.tga
bigrock_rounded_faint.tga
bunkertrim3_snow.tga
bunkertrim_snow.tga
bunkerwall_lrg02.tga
coal_snow.tga
concretec05_snow.tga
fuse_box_snow.tga
icelake2.tga
icelake3.tga
mesh_c03_snow.tga
metal_m04g2_snow.tga
miltary_m04_snow.tga
mroof_snow.tga
mxrock4b_snow.tga
river_edge_snowy.tga
snow_muddy.jpg
snow_noisy.tga
snow_path01.tga
snow_road01.tga
snow_track03.tga
snow_track03_end.tga
snow_var01.tga
snow_var01_big.tga
snow_var02.tga
sub1_snow.tga
sub1_snow2.tga
s_castle_m03a_trim.tga
s_dirt_m03i_2_big.tga
s_grass_ml03b_big.jpg
wood_m05a_snow.tga
xmetal_m02t_snow.tga
xmetal_m02_snow.tga
=================================== ======== ============ =========== ======== ============= =============================


stone
-----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
mxdebri0_riverbed.tga
mxrock1aa.jpg
mxrock3h_snow.tga
mxrock3_a.jpg
mxsnow2.tga
mxsnow3.tga
=================================== ======== ============ =========== ======== ============= =============================


swf
---

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
ametal_m08.jpg
door_loper.jpg
door_m01aaaaswf.jpg
door_m01aswf.jpg
door_m01swf.jpg
fuse_box.jpg
fuse_box1a.jpg
fuse_box2.jpg
metal_m01.jpg
metal_m02.jpg
metal_m03.jpg
spipe_02.jpg
spipe_03.jpg
spipe_04.jpg
spipe_05a.jpg
xtrim_cm05.jpg
=================================== ======== ============ =========== ======== ============= =============================


temperate_sd
------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
dirt3.tga
dirt_m03icmp_brown.jpg
dirt_m04cmp_brown.jpg
grass_dense1.tga
grass_path1.tga
master_grass_dirt3.tga
road_bigpuddle.tga
road_puddle1.tga
rocky_sand.tga
rock_graynoise.tga
rock_grayvar.tga
rock_ugly_brown.tga
sand_bubbles_bright.tga
sand_disturb_bright.tga
sand_patchnoise.tga
sand_wave_bright.tga
=================================== ======== ============ =========== ======== ============= =============================


terrain
-------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
dirt_m03g3.tga
dirt_m03i.jpg
=================================== ======== ============ =========== ======== ============= =============================


tobruk_roof_sd
--------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
tobruk_roof2.jpg
=================================== ======== ============ =========== ======== ============= =============================


tobruk_wall_sd
--------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
tobruk_wall_base1.jpg
tobruk_wall_base2.jpg
tobruk_wall_base3.jpg
tobruk_wall_base4.jpg
tobruk_wall_base5.jpg
tobruk_wall_base6.jpg
tobruk_wall_base7.jpg
tobruk_wall_base8.jpg
tobruk_wall_base9.jpg
=================================== ======== ============ =========== ======== ============= =============================


tobruk_windows_sd
-----------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
tobruk_lwind1.jpg
tobruk_lwind2.jpg
tobruk_moucha1.tga
tobruk_mwind1.jpg
tobruk_mwind2.jpg
tobruk_shutterbrown.jpg
tobruk_windows_off.jpg
tobruk_windows_on1.jpg
tobruk_windows_on2.jpg
=================================== ======== ============ =========== ======== ============= =============================


town_floor
----------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
floor_d01.jpg
=================================== ======== ============ =========== ======== ============= =============================


town_roof
---------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
roof_c02.jpg
roof_c03a.jpg
=================================== ======== ============ =========== ======== ============= =============================


town_wall
---------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
church_c01dm.jpg
town_c38a.jpg
town_c61a.jpg
town_c91.jpg
town_m_c01.jpg
=================================== ======== ============ =========== ======== ============= =============================


town_window
-----------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
shudder_c04.jpg
window_c05a.jpg
=================================== ======== ============ =========== ======== ============= =============================


town_wood
---------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
wood_c01.jpg
wood_c08.jpg
=================================== ======== ============ =========== ======== ============= =============================


tree
----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
trunck3a.jpg
=================================== ======== ============ =========== ======== ============= =============================


village
-------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
vill2_win_m2.tga
villwin_c08dm.jpg
villwin_c12m.tga
villwin_c15.blend.jpg
villwin_c15.jpg
=================================== ======== ============ =========== ======== ============= =============================


village_interior
----------------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
inter_c11_ba.jpg
=================================== ======== ============ =========== ======== ============= =============================


wood
----

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
wood_c01.jpg
wood_m01_usat.jpg
wood_m02.jpg
wood_m02a.jpg
wood_m05a_usat.jpg
wood_m05a_usata.jpg
wood_m05a_usata_dm.jpg
wood_m06a.jpg
wood_m12.jpg
wood_m13.jpg
wood_m13_usat.tga
wood_m15.jpg
wood_m16.jpg
wood_m16cm.jpg
wood_m18.jpg
=================================== ======== ============ =========== ======== ============= =============================


xlab_floor
----------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
xfloor_c01.jpg
xfloor_c05.jpg
xfloor_c07.jpg
=================================== ======== ============ =========== ======== ============= =============================


xlab_props
----------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
panel_m01.jpg
xdrawers_c03.jpg
xgrid_c01.jpg
xpanel_c02dm.jpg
xpanel_c05_light_half.jpg
xpanel_c08.jpg
xpanel_c10_light.jpg
xradio_c02.jpg
=================================== ======== ============ =========== ======== ============= =============================


xlab_wall
---------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
xconcrete_c54.jpg
xconcrete_c54_c.jpg
xconcrete_c58.jpg
xconcrete_c58m.jpg
xmetal_c03.jpg
xmetal_m02a.tga
xmetal_m03l.tga
xtrim_c04.jpg
xtrim_c06.jpg
XTRIM_C07.jpg
xwall_c09.jpg
xwall_c10.jpg
=================================== ======== ============ =========== ======== ============= =============================


ui
==

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
credits_activision.menu
credits_additional.menu
credits_idsoftware.menu
credits_quit.menu
credits_splashdamage.menu
global.menu
hostgame.menu
hostgame_advanced.menu
hostgame_advanced_default.menu
hostgame_dedicated_warning.menu
ingame_disconnect.menu
ingame_main.menu
ingame_messagemode.menu
ingame_serverinfo.menu
ingame_tapout.menu
ingame_tapoutlms.menu
ingame_vote.menu
ingame_vote_disabled.menu
ingame_vote_map.menu
ingame_vote_misc.menu
ingame_vote_misc_refrcon.menu
ingame_vote_players.menu
ingame_vote_players_warn.menu
main.menu
menudef.h
menumacros.h
menus.txt
options.menu
options_controls.menu
options_controls_default.menu
options_customise_game.menu
options_customise_hud.menu
options_system.menu
options_system_gamma.menu
playonline.menu
playonline_connecttoip.menu
playonline_disablepb.menu
playonline_enablepb.menu
playonline_serverinfo.menu
popup_autoupdate.menu
popup_errormessage.menu
popup_errormessage_pb.menu
popup_hostgameerrormessage.menu
popup_password.menu
profile.menu
profile_create.menu
profile_create_error.menu
profile_create_initial.menu
profile_delete.menu
profile_delete_error.menu
profile_rename.menu
quit.menu
rec_restart.menu
vid_confirm.menu
vid_restart.menu
viewreplay.menu
viewreplay_delete.menu
wm_ftquickmessage.menu
wm_ftquickmessageAlt.menu
wm_quickmessage.menu
wm_quickmessageAlt.menu
=================================== ======== ============ =========== ======== ============= =============================


assets
------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
3squares.tga
3_cursor3.tga
background_mask.tga
blackgrad.tga
check.tga
check_no.tga
check_not.tga
clouds.tga
et_logo.tga
et_logo_huge.tga
fadebox.tga
filter_antilag.tga
filter_balance.tga
filter_emptyfull.tga
filter_ff.tga
filter_lives.tga
filter_pass.tga
filter_pb.tga
filter_weap.tga
gammabar.tga
gradientbar1.tga
gradientbar2.tga
hudsprint.tga
logo_atvi.tga
logo_gm.tga
logo_id.tga
logo_nerve.tga
logo_osp.tga
logo_pb.tga
logo_sd.tga
mp_ammo_blue.tga
mp_ammo_red.tga
mp_arrow_blue.tga
mp_arrow_red.tga
mp_gun_blue.tga
mp_gun_red.tga
mp_health_blue.tga
mp_health_red.tga
mp_player_highlight.tga
mp_spy_blue.tga
mp_spy_red.tga
mp_wrench_blue.tga
mp_wrench_red.tga
radio_tower.tga
ring.tga
scrollbar.tga
scrollbar_arrow_dwn_a.tga
scrollbar_arrow_left.tga
scrollbar_arrow_right.tga
scrollbar_arrow_up_a.tga
scrollbar_thumb.tga
slider2.tga
sliderbutt_1.tga
=================================== ======== ============ =========== ======== ============= =============================


portraits
^^^^^^^^^

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
allies_win_flag.jpg
axis_win_flag.jpg
text_allies.tga
text_axis.tga
text_win.tga
=================================== ======== ============ =========== ======== ============= =============================


assets2
-------

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
maptrim_edge.tga
maptrim_long.tga
maptrim_long2.tga
stamp_complete.tga
stamp_failed.tga
=================================== ======== ============ =========== ======== ============= =============================


weapons
=======

=================================== ======== ============ =========== ======== ============= =============================
File                                Status   Author       Resources   Origin   Last Updated  Notes
=================================== ======== ============ =========== ======== ============= =============================
adrenaline.weap
akimbo_colt.weap
akimbo_luger.weap
akimbo_silenced_colt.weap
akimbo_silenced_luger.weap
ammopack.weap
binocs.weap
colt.weap
dynamite.weap
fg42.weap
flamethrower.weap
gpg40.weap
grenade.weap
k43.weap
kar98.weap
knife.weap
landmine.weap
luger.weap
m1_garand.weap
m1_garand_s.weap
m7.weap
mapmortar.weap
medpack.weap
mg42.weap
mortar.weap
mortar_set.weap
mp40.weap
panzerfaust.weap
pineapple.weap
pliers.weap
satchel.weap
satchel_det.weap
silenced_colt.weap
silenced_luger.weap
smokegrenade.weap
smokemarker.weap
smoketrail.weap
sten.weap
syringe.weap
thompson.weap
=================================== ======== ============ =========== ======== ============= =============================
