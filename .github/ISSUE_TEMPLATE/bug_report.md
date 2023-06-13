---
name: Bug report
about: Keyboard dismisses slow
title: Keyboard dismisses slow
labels: ''
assignees: ''

---

**Description**
Soft Keyboard dismisses slow after Updating Xamarin.Forms version to 5.+

**To Reproduce**
Steps to reproduce the behavior:
1. Tabbed Page > Content Page with Editor Control
2. Focus the Editor
3. Unfocus the Editor

**Expected behavior**
 Can see a white space for Half a second Approximately



**Screenshots**
If applicable, add screenshots to help explain your problem.

**Smartphone :**
 - Device: Moto g power(Android 11), One Plus Nod CE2(Android 13) 
 - OS : Android
 - Version Checked  Android 7.1.1 - 13

**Additional context**

 Follwing snippet on OnParentset 
Xamarin.Forms.Application.Current.On<Xamarin.Forms.PlatformConfiguration.Android>().UseWindowSoftInputModeAdjust(WindowSoftInputModeAdjust.Resize);

**Note**
We get this issue only after updating Xamarin.Forms to 5.+
