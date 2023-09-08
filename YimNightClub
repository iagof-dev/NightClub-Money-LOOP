title = "NightClub Money v0.2"
mp0_t = "MP0_CLUB_PAY_TIME_LEFT"
mp0_p = "MP0_CLUB_POPULARITY"
mp1_t = "MP1_CLUB_PAY_TIME_LEFT"
mp1_p = "MP1_CLUB_POPULARITY"
ult = gui.get_tab(title)
gui.show_warning(title)
ult:add_text("Just open nightclub safe and start the script.")
ult:add_text("**USE AT YOUR OWN RISK**")

checkbox = ult:add_checkbox("Enable")
script.register_looped("nightclubloop", function(script)
    script:yield()
    if checkbox:is_enabled() == true then
	      log.info("Script iniciado...")
        STATS.STAT_SET_INT(joaat(mp0_p), 1000, true)
        STATS.STAT_SET_INT(joaat(mp0_t), -1, true)
	      STATS.STAT_SET_INT(joaat(mp1_p), 1000, true)
        STATS.STAT_SET_INT(joaat(mp1_t), -1, true)
	      log.info("Script Finalizado")
        script:sleep(1250)
    end
end)
