# Nice-Vibrations
Vibration for game unity
```
"com.graywolves.nicevibrations": "https://github.com/GrayWolves/Nice-Vibrations.git#1.0.1",
```
How to use?
- You need to add the above link in manifest.json in folder Package
- Using library in your class.
```
using MoreMountains.NiceVibrations;
```
- Enables or disables all haptics called via this class (enable with status true and desable with status false)
```
MMVibrationManager.SetHapticsActive(true);
```
- Triggers a haptic feedback of the specified type
```
MMVibrationManager.Haptic(HapticTypes.MediumImpact);
```
- HapticTypes include (``Selection, Success, Warning, Failure, LightImpact, MediumImpact, HeavyImpact, RigidImpact, SoftImpact, None``). You should choose the haptic style that suits your purpose

(Package is attached at release)
