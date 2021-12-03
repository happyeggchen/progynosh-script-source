crescent
============
    A tool to set up a tui quickly
      Include:
        6 functions
          {crescent-gauge,crescent-choose,crescent-input,crescent-inputmenu,crescent-backend}
      Usage:
        gauge argv[2] argv[3] argv[4]
          argv[2] -> crescent_title
          argv[3] -> crescent_title_gauge
          argv[4] -> crescent_gauge_percent
        choose argv[2] argv[3] argv[4+]
          argv[2] -> crescent_title
          argv[3] -> crescent_title_menu
          argv[4] -> crescent_menu_list
        input argv[2] argv[3] argv[4]
          argv[2] -> crescent_title
          argv[3] -> crescent_title_text
          argv[4] -> crescent_text_init
        inputmenu argv[2] argv[3] argv[4..-1]
          argv[2] -> crescent_title
          argv[3] -> crescent_title_menu_text_input
          argv[4] -> crescent_menu_list_text (two as a gruop likes 'hi' '',the second argv will be treated as init vaule,leave blank for nothing)
