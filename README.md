 [code]

I'm sorry, but an uncaught exception occurred.



While running game code:

Exception: Open text tag at end of string u'{P\xeddele a Judy que te ayude con Celia.'.



-- Full Traceback ------------------------------------------------------------



Full traceback:

  File "scripts/school/therapist_room/morning/scenes/judy_morning_scene1_v1.rpyc", line 27, in script

  File "renpy/ast.py", line 1628, in execute

  File "renpy/exports.py", line 990, in menu

  File "renpy/exports.py", line 1226, in display_menu

  File "renpy/ui.py", line 297, in interact

  File "renpy/display/core.py", line 2702, in interact

  File "renpy/display/core.py", line 3094, in interact_core

  File "renpy/display/core.py", line 541, in visit_all

  File "renpy/display/core.py", line 541, in visit_all

  File "renpy/display/core.py", line 541, in visit_all

  File "renpy/display/screen.py", line 434, in visit_all

  File "renpy/display/core.py", line 541, in visit_all

  File "renpy/display/core.py", line 541, in visit_all

  File "renpy/display/core.py", line 541, in visit_all

  File "renpy/display/core.py", line 531, in visit_all

  File "renpy/text/text.py", line 1717, in visit

  File "renpy/text/text.py", line 1694, in update

  File "renpy/text/text.py", line 2164, in tokenize

  File "textsupport.pyx", line 122, in renpy.text.textsupport.tokenize

Exception: Open text tag at end of string u'{P\xeddele a Judy que te ayude con Celia.'.



[/code]

