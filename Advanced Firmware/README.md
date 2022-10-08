Stock Firmware is parallel to the official firmware with features enabled.
 <br> --Linear Advance with K=0 so it won't affect anything unless you set it up.
 <br> --Fade height set to a more reasonable 5.0mm instead of 50.0mm.
 <br> --Power Loss Recovery disabled since it is buggy.
 <br> --Host Action Commands enabled.
 <br> --Advanced Pause Enabled with M600 support, though there seems to be an issue with resuming a print after filament change.
 <br> --PID for the Bed instead of Bang-Bang.
 <br> --S-Curve Acceleration enabled.
 <br> --M48 Probe Repeatability Test enabled.
 <br> --G26 Mesh Validation Enabled.
<br><br>
Dual Independent Z firmware requires a TMC2208 driver in the spare slot on the control board which will require manual vref setting.
<br><br>
Dual Extruder firmware also requires a TMC2208 driver.
<br><br>
Dual Independent Z and Dual Extruder are mutually exclusive and cannot be used together as there is only one available driver socket. You can however do split driver dual Z and Dual Extruders. Additional hardware will also be needed for both options. Both of these firmwares are untested so use at your own risk and let me know if you have any issues with them.
