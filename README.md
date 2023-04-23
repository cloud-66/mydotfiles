# mydotfiles
1.  Open windows store and install windows terminal and powershell
2.  install scoop
3.  add scoop extras,nerd-fonts
4.  select default profile : "Powershell"
5.  Make Consolas Nerd fonts
   - Copy fonts consolas C:\Windows\Fonts to `\\wsl.localhost\Ubuntu-20.04\home\cloud\musor\Consolas-Font`
  ```
   docker run --rm -v /home/cloud/musor/Consolas-Font:/in -v /home/cloud/musor/consolas:/out nerdfonts/patcher --fontawesome --fontawesomeextension --powerline --fontlogos --octicons --codicons --powersymbols --pomicons --powerlineextra --weather --windows --material
   ```
6. install generated font. Select fonts, right click `install for all users`
7. Open windows terminal json settings. Copy One Half Dark theme to `One Half Dard (Modded)`.
   Change backgroupd to `#1C3145`



