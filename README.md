# CSGO-AUTOEXEC-2019
SHARE TWEET  LEGACY CSGO AUTOEXEC - $RICH-GANG$ CFG'S


clear
unbindall
unbindallmousekeyboard


unbindall
unbindallmousekeyboard

//Slots
bind "0" "slot10"
bind "1" "slot1"
bind "2" "slot2"
bind "3" "slot3"
bind "4" "slot4"
bind "5" "slot5"
bind "6" "slot6"
bind "7" "slot7"
bind "8" "slot8"
bind "9" "slot9"

//Movement
bind "a" "+moveleft"
bind "d" "+moveright"
bind "s" "+back"
bind "w" "+forward"
bind "MWHEELDOWN" "+jump"
bind "SHIFT" "+speed"
bind "CTRL" "+duck"

//Usage & Equip
bind "b" "buymenu"
bind "e" "+use"
bind "q" "lastinv"
bind "r" "+reload"
bind "g" "drop"
bind "F3" "autobuy"
bind "F4" "rebuy"
bind "MWHEELUP" "invprev"

//Attack
bind "MOUSE1" "+attack"
bind "MOUSE2" "+attack2"

//Chat
bind "o" "+radio3;radio3"
bind "ALT" "+voicerecord"
bind "u" "messagemode2"
bind "z" "messagemode"

//misc binds
bind "m" "teammenu"
bind "c" "toggleconsole"
bind "ESCAPE" "cancelselect"
bind "f" "+lookatweapon;"
bind "h" "+spray_menu"

snd_menumusic_volume "0"
snd_mix_async "1"
snd_mixahead "0.025"

cl_lagcompensation "1"
cl_predict "1"
cl_predictweapons "1"
cl_interp "0"
cl_interp_ratio "1"
cl_cmdrate "128"
cl_updaterate "128"
rate "786432"
//Misc
mm_dedicated_search_maxping "100"
cl_use_opens_buy_menu "0"
con_enable "1"
cl_dm_buyrandomweapons "0"
cl_teammate_colors_show "1"
cl_autowepswitch "0"
cl_autohelp "0"
cl_disablehtmlmotd "0"
cl_downloadfilter "nosounds"
cl_showhelp "0"
cl_forcepreload "1" 
r_dynamic "1"
joystick "0"



//HUD
cl_hud_background_alpha "0.85"
cl_hud_color "10"
cl_hud_playercount_showcount "1"
cl_hud_playercount_pos "1"
cl_show_clan_in_death_notice "1"
cl_hud_bomb_under_radar "1"
cl_hud_healthammo_style "1"
cl_showloadout "1"
cl_loadout_colorweaponnames "1"
hud_showtargetid "1"

//Video tweaks
r_dynamic "1"

//viewmodels 
cl_viewmodel_shift_left_amt "0.500000"
cl_viewmodel_shift_right_amt "0.250000"
viewmodel_fov "60"
viewmodel_offset_x "-2"
viewmodel_offset_y "-2"
viewmodel_offset_z "-2"
viewmodel_presetpos "0"
cl_bob_lower_amt "5.000000"
cl_bobamt_lat "0.100000"
cl_bobamt_vert "0.100000"
cl_bobcycle "0.98"


//Crosshair
cl_crosshairstyle "4"
cl_crosshaircolor "5"
cl_crosshaircolor_r "210"
cl_crosshaircolor_g "49"
cl_crosshaircolor_b "251"
cl_crosshairalpha "175"
cl_crosshair_drawoutline "1"
cl_crosshair_outlinethickness "0.6"
cl_crosshairthickness "0.82"
cl_crosshairsize "1.85"
cl_crosshairgap "-2.25"
cl_crosshair_dynamic_maxdist_splitratio "0.25"
cl_crosshairdot "0"

// Mouse Sense
// DPI = 600
sensitivity "1.15"
zoom_sensitivity_ratio_mouse "1"
m_rawinput "1"
m_customaccel "0"
m_mousespeed "0"
m_mouseaccel1 "0"
m_mouseaccel2 "0"





//Jump-throw script
alias "+jumpthrow" "+jump;-attack" 
alias "-jumpthrow" "-jump" 
bind "MOUSE5" "+jumpthrow"
bind "MOUSE4" "+jumpthrow"

//Scores + show netgraph
alias "+ng" "+showscores; net_graph 1"
alias "-ng" "-showscores; net_graph 0"
bind "TAB" "+ng"



mat_savechanges
host_writeconfig

clear

echo "   "
echo "   "
echo "   "
echo "   "
echo "   "
echo "   "
echo "   "
echo "   "
echo "  #########################################################################################################################  "
echo "  .........................................................................................................................  "
echo "   "
echo "  ██╗.....███████╗.██████╗..█████╗..██████╗██╗...██╗.....█████╗.██╗...██╗████████╗.██████╗.███████╗██╗..██╗███████╗.██████╗  "
echo "  ██║.....██╔════╝██╔════╝.██╔══██╗██╔════╝╚██╗.██╔╝....██╔══██╗██║...██║╚══██╔══╝██╔═══██╗██╔════╝╚██╗██╔╝██╔════╝██╔════╝  "
echo "  ██║.....█████╗..██║..███╗███████║██║......╚████╔╝.....███████║██║...██║...██║...██║...██║█████╗...╚███╔╝.█████╗..██║.....  "
echo "  ██║.....██╔══╝..██║...██║██╔══██║██║.......╚██╔╝......██╔══██║██║...██║...██║...██║...██║██╔══╝...██╔██╗.██╔══╝..██║.....  "
echo "  ███████╗███████╗╚██████╔╝██║..██║╚██████╗...██║.......██║..██║╚██████╔╝...██║...╚██████╔╝███████╗██╔╝.██╗███████╗╚██████╗  "
echo "  ╚══════╝╚══════╝.╚═════╝.╚═╝..╚═╝.╚═════╝...╚═╝.......╚═╝..╚═╝.╚═════╝....╚═╝....╚═════╝.╚══════╝╚═╝..╚═╝╚══════╝.╚═════╝  "
echo "   "
echo "  .........................................................................................................................  "
echo "  #########################################################################################################################  "
echo "   "
echo "   "
echo "   "
echo "   "
echo "   "
echo "  ########################################################################################################################## "
echo "  .........................................................................................................................  "
echo "   "
echo "  ...............▄▄███▄▄·██████╗.██╗.██████╗██╗..██╗.......██████╗..█████╗.███╗...██╗.██████╗.▄▄███▄▄·.....................  "
echo "  ...............██╔════╝██╔══██╗██║██╔════╝██║..██║......██╔════╝.██╔══██╗████╗..██║██╔════╝.██╔════╝.....................  "
echo "  ...............███████╗██████╔╝██║██║.....███████║█████╗██║..███╗███████║██╔██╗.██║██║..███╗███████╗.....................  "
echo "  ...............╚════██║██╔══██╗██║██║.....██╔══██║╚════╝██║...██║██╔══██║██║╚██╗██║██║...██║╚════██║.....................  "
echo "  ...............███████║██║..██║██║╚██████╗██║..██║......╚██████╔╝██║..██║██║.╚████║╚██████╔╝███████║.....................  "
echo "  ...............╚═▀▀▀══╝╚═╝..╚═╝╚═╝.╚═════╝╚═╝..╚═╝.......╚═════╝.╚═╝..╚═╝╚═╝..╚═══╝.╚═════╝.╚═▀▀▀══╝  "
echo "   "
echo "  .........................................................................................................................  "
echo "  #########################################################################################################################  "
