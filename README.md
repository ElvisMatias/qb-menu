# qb-menu with movement


PREVIEW: https://streamable.com/3bqymc

the client side file is attached where it incorporates the function to use it in motion
It is not finished, it still has a problem that when pressing on an event then the menu does not allow to move the camera with the mouse, pressing the F3 key is solved
(Line 140)

any contribution is welcome for use

 if IsControlJustReleased(0, 170) then --F3
 
 ----
     SetNuiFocus(false, false)
    SetNuiFocusKeepInput(false)
    active = false
