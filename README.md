# -ESC-GetPos-
Func Example() HotKeySet("{ESC}", "GetPos") GUICreate("Press Esc to Get Pos", 400, 400) $g_idX = GUICtrlCreateLabel("0", 10, 10, 50) $g_idY = GUICtrlCreateLabel("0", 10, 30, 50) GUISetState(@SW_SHOW) ; Loop until the user exits.While 1
