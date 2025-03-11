::: MmD
@ECHO OFF
set "params=%*"
cd /d "%~dp0" && ( if exist "%temp%\getadmin.vbs" del "%temp%\getadmin.vbs" ) && fsutil dirty query %systemdrive% 1>nul 2>nul || (  echo Set UAC = CreateObject^("Shell.Application"^) : UAC.ShellExecute "cmd.exe", "/k cd ""%~sdp0"" && %~s0 %params%", "", "runas", 1 >> "%temp%\getadmin.vbs" && "%temp%\getadmin.vbs" && exit /B )
color a
cls
echo     R6 Killer
echo -----------------
echo     I hate R6
echo;
pause
taskkill /F /IM BEService_x64.exe
taskkill /F /IM Cleaner.exe
taskkill /F /IM FirewallInstall.exe
taskkill /F /IM RainbowSix.exe
taskkill /F /IM RainbowSix_BE.exe
taskkill /F /IM RainbowSix_DX11.exe
taskkill /F /IM RainbowSix_Vulkan.exe
taskkill /F /IM SharePlayClient.exe
taskkill /F /IM UbisoftConnect.exe
taskkill /F /IM UbisoftConnectInstaller.exe
taskkill /F /IM UbisoftExtension.exe
taskkill /F /IM UbisoftGameLauncher.exe
taskkill /F /IM UbisoftGameLauncher64.exe
taskkill /F /IM Uninstall.exe
taskkill /F /IM UpcElevationService.exe
taskkill /F /IM UplayCrashReporter.exe
taskkill /F /IM UplayService.exe
taskkill /F /IM UplayWebCore.exe
taskkill /F /IM scimitar_engine_win64_2022_flto_dx11.exe
taskkill /F /IM upc.exe
cls
echo KILLED !
pause
exit
