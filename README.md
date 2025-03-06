# Need for Speed Carbon: Performance Rework Mod  

*By Platanito22*  

![Screenshots\7.jpg](https://github.com/JesusRondon2310/Need-for-Speed-Carbon-Perfomance-Rework/blob/main/Nfs%20Carbon%20Performance%20Reworking/Screenshots/7.png)]  

**⚠️ NOTE:** English translation provided below/Spanish version available in [README-ES.md] 

---

## 🔍 Overview  

Have you ever imagined what Need for Speed ​​Carbon would be like with the performance of the cars from Most Wanted? Yes, well that's what
this mod comes to make a reality, it wasn't very disappointing to see how the M3 GTR went from reaching 389 kph and having amazing maneuverability
in Most Wanted that became a car with limited maneuverability, average acceleration and a top speed of only 322 kph
(don't get me wrong 322 kph is low for a Need for Speed ​​from the black box era and even more so being the direct sequel to Most Wanted,
but in real life it is high).

Well that's what this mod comes to do, in short port and improve the performance of the more than 50 cars from Need for Speed ​​Carbon
the performance of all the Most Wanted cars present in Carbon and the exclusive ones from Carbon such as the CCX or the Skyline R34.

---

## 🚀 Features  

### 🏎️ Core Improvements  

- **Performance Improvements**:
- Acceleration and top speeds ported from Most Wanted (M3 GTR: 322kph → 389kph)
- Some car Tiers rejigged
- Price changes (in order to accommodate cars)
- Fixed wheel alignment and some bodykit issues

### 🛠️ Advanced Mechanics  

  - "Realistic" Turbo Functionality  
  - Supercharger tweaks  

- **Vehicle Reworks**:  
  - Complete overhauls (e.g., Alfa Romeo Brera)  
  - Buff/Nerf adjustments (e.g., Murciélago: 396kph → 390kph)   

---

## ⚙️ Installation  

There are several options for VlTed and OVGI:
(make a backup of the files before installing the mod you know)

1. Each Car has a .nfsms, so you can try each one individually, they are in different folders, one is for vanilla and another for the
improvement mod.

2. There is a .nfsms that installs the performance of all cars instantly.

3. And finally there is a folder that says Optionals that are just added and another that says Better Cameras which is the camera configuration that I use
to play the game I put them there in case you want to try them :)

### Requirements  

- Need for Speed Carbon (v1.4 recommended)  
- Modding Tools:  
  - [VlTed](https://nfs-tools.blogspot.com/2019/02/nfs-vlted-v46-released.html)  
  - [OVGI](https://nfsmods.xyz/mod/5290)
  - [Binary](https://nfsmods.xyz/mod/1638)  

### Steps  

**Choose Installation Method**:
- Full Package: With ovgi or vlted, go to File, then import, select ModScript option and select the `all in 1.nfsms` file,
after that a box will appear with the `install` button, when finished go back to `File` and press `Save` and that's it!

- Manual Selection: Individual `.nfsms` files per car

### 🎨 Optional Add-ons

- New Colors: Applied With Binary
- Unlocked Bonus Cars
- Improved Cameras (Personal Configuration)
---

## ⚠️ Important Notes  

For those interested in knowing more:

<!-- Well, speaking of the ["Realistic" Turbo and Supercharger Operation] section, well, like turbos in real life, this mod comes to replicate them, bringing with it the famous and scary [Turbo-Lag],
but it is not as much as you are imagining, that is, it does not take 5 business days to charge the turbo as it happens in real life, it is more gameplay friendly, that is, the final effect
that I wanted to achieve by bringing the turbo lag is not the time it takes to charge the turbo but the kick that the turbo gives when it is at 100% operation, if you want to know what I was guided
by to replicate it here I leave you a link to a youtube video of a dyno with metrics `https://youtu.be/NxL3luSwLL0?si=YlBJ-cxv9e2cjYlB`, as you could see if you saw the video the operation of the turbo lag
is similar with this mod, the turbo is activated at a certain rpm (each car has its own) and the turbo kick is noticeable when it reaches 100% use, you can see the operation
with a hud from `https://nfsmods.xyz/mod/1903` or use the one I use `https://nfsmods.xyz/mod/6169`, but that is what I mean by turbo lag and in case you want to know the Supercharger does not have turbo lag,
but it is not broken. -->

## NODE CHANGES

- Brakes
- Chassis
- Ecar
- Engine
- Frontend
- Induction
- Pvehicle
- Presetride
- Shiftpattern (only for bmw m3 gtr)
- Tires
- Transmission

---

## 📜 Modding Details  

### Modified Files  

```text
📦Nfs Carbon Performance Reworking
 ┣ 📂Optionals
 ┃ ┣ 📂Better Cameras
 ┃ ┃ ┗ 📜CAMERAS_REVAMP.nfsms
 ┃ ┗ 📜Unlock Bonus cars.nfsms
 ┗ 📂Reworking
 ┃ ┣ 📂Improvement mod
 ┃ ┃ ┣ 📂ovgi
 ┃ ┃ ┃ ┣ 📂Carbon Cars
 ┃ ┃ ┃ ┃ ┣ 📂240sx
 ┃ ┃ ┃ ┃ ┃ ┗ 📜240SX_RB26_SWAP.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂300c
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_300C.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂350z
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_350Z.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂997tt
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_997TT.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂audi lemans
 ┃ ┃ ┃ ┃ ┃ ┗ 📜LEMANS_R8_BETTER_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂brera
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_BRERA.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂camaro 65
 ┃ ┃ ┃ ┃ ┃ ┗ 📜LSX_65_CAMARO_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂camaro concept
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CAMARO_CONCEPT.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂ccx
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CCX.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂Challenger 71
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHALLENGER71.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂challengern
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHALLENGER_CONCEPT.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂charger srt8
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHARGER06.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂charger69
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHARGER69.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂chevelle
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHEVELLE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂cobra 07
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_COBRA_07.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂corolla
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_COROLLA.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂eclipse
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_ECLIPSE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂europa s
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_EUROPAS.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂evo9
 ┃ ┃ ┃ ┃ ┃ ┗ 📜evo9_10k_rpm.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂ford gt
 ┃ ┃ ┃ ┃ ┃ ┗ 📜FORD_GT_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂g35
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_G35.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂gt3 rs (997)
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_997GT3RS.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂gt500
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_GT500.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂hemi cuda
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_HEMI_CUDA.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂jaguar xk
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_XK.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂mazda speed 3
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_MAZDASPEED3.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂mr2
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_MR2.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂r32
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_R32.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂roadrunner
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_ROADRUNNER.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂skyline r34
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_SKYLINE_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂sl65
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_SL65.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂slr
 ┃ ┃ ┃ ┃ ┃ ┗ 📜SLR_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┗ 📂zonda
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_ZONDA.nfsms
 ┃ ┃ ┃ ┣ 📂Most Wanted Cars
 ┃ ┃ ┃ ┃ ┣ 📂bmw m3 gtr mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BMW_M3_GTR_E46_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂carrera gt mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CARRERA_GT_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂Cayman s
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CAYMANS_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂Clio
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CLIO_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂clk500
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CLK500_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂corvette z06 mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CORVETTE_Z06_MW_SIMILAR_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂db9
 ┃ ┃ ┃ ┃ ┃ ┗ 📜DB9_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂eclipse gt
 ┃ ┃ ┃ ┃ ┃ ┗ 📜ECLIPSEGT_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂elise
 ┃ ┃ ┃ ┃ ┃ ┗ 📜ELISE_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂gallardo mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜GALLARDO_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂Gto mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_GTO.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂is300
 ┃ ┃ ┃ ┃ ┃ ┗ 📜IS300_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂lamborghini murcielago
 ┃ ┃ ┃ ┃ ┃ ┗ 📜MURCIELAGO&LP640_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂monaro
 ┃ ┃ ┃ ┃ ┃ ┗ 📜MONARO_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂mustang mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜MUSTANGGT_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂rx7 mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜RX7_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂rx8 mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜RX8_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂subaru impreza wrx carbon
 ┃ ┃ ┃ ┃ ┃ ┗ 📜IMPREZA_STI_MW.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂supra mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜SUPRA_STUTUTU.nfsms
 ┃ ┃ ┃ ┃ ┗ 📂viper
 ┃ ┃ ┃ ┃ ┃ ┗ 📜VIPER_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┗ 📜all in 1.nfsms
 ┃ ┃ ┗ 📂Vlted
 ┃ ┃ ┃ ┣ 📂Carbon Cars
 ┃ ┃ ┃ ┃ ┣ 📂240sx
 ┃ ┃ ┃ ┃ ┃ ┗ 📜240SX_RB26_SWAP.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂300c
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_300C.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂350z
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_350Z.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂997tt
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_997TT.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂audi lemans
 ┃ ┃ ┃ ┃ ┃ ┗ 📜LEMANS_R8_BETTER_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂brera
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_BRERA.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂camaro 65
 ┃ ┃ ┃ ┃ ┃ ┗ 📜LSX_65_CAMARO_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂camaro concept
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CAMARO_CONCEPT.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂ccx
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CCX.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂Challenger 71
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHALLENGER71.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂challengern
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHALLENGER_CONCEPT.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂charger srt8
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHARGER06.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂charger69
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHARGER69.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂chevelle
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHEVELLE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂cobra 07
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_COBRA_07.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂corolla
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_COROLLA.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂eclipse
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_ECLIPSE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂europa s
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_EUROPAS.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂evo9
 ┃ ┃ ┃ ┃ ┃ ┗ 📜evo9_10k_rpm.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂ford gt
 ┃ ┃ ┃ ┃ ┃ ┗ 📜FORD_GT_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂g35
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_G35.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂gt3 rs (997)
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_997GT3RS.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂gt500
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_GT500.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂hemi cuda
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_HEMI_CUDA.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂jaguar xk
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_XK.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂mazda speed 3
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_MAZDASPEED3.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂mr2
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_MR2.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂r32
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_R32.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂roadrunner
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_ROADRUNNER.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂skyline r34
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_SKYLINE_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂sl65
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_SL65.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂slr
 ┃ ┃ ┃ ┃ ┃ ┗ 📜SLR_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┗ 📂zonda
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_ZONDA.nfsms
 ┃ ┃ ┃ ┣ 📂Most Wanted Cars
 ┃ ┃ ┃ ┃ ┣ 📂bmw m3 gtr mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BMW_M3_GTR_E46_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂carrera gt mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CARRERA_GT_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂Cayman s
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CAYMANS_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂Clio
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CLIO_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂clk500
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CLK500_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂corvette z06 mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CORVETTE_Z06_MW_SIMILAR_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂db9
 ┃ ┃ ┃ ┃ ┃ ┗ 📜DB9_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂eclipse gt
 ┃ ┃ ┃ ┃ ┃ ┗ 📜ECLIPSEGT_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂elise
 ┃ ┃ ┃ ┃ ┃ ┗ 📜ELISE_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂gallardo mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜GALLARDO_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂Gto mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_GTO.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂is300
 ┃ ┃ ┃ ┃ ┃ ┗ 📜IS300_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂lamborghini murcielago
 ┃ ┃ ┃ ┃ ┃ ┗ 📜MURCIELAGO&LP640_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂monaro
 ┃ ┃ ┃ ┃ ┃ ┗ 📜MONARO_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂mustang mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜MUSTANGGT_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂rx7 mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜RX7_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂rx8 mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜RX8_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂subaru impreza wrx carbon
 ┃ ┃ ┃ ┃ ┃ ┗ 📜IMPREZA_STI_MW.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂supra mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜SUPRA_STUTUTU.nfsms
 ┃ ┃ ┃ ┃ ┗ 📂viper
 ┃ ┃ ┃ ┃ ┃ ┗ 📜VIPER_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┗ 📜all in 1.nfsms
 ┃ ┗ 📂vanilla
 ┃ ┃ ┣ 📂ovgi
 ┃ ┃ ┃ ┣ 📂Carbon Cars
 ┃ ┃ ┃ ┃ ┣ 📂240sx
 ┃ ┃ ┃ ┃ ┃ ┗ 📜240SX_RB26_SWAP.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂300c
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_300C.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂350z
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_350Z.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂997tt
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_997TT.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂audi lemans
 ┃ ┃ ┃ ┃ ┃ ┗ 📜LEMANS_R8_BETTER_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂brera
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_BRERA.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂camaro 65
 ┃ ┃ ┃ ┃ ┃ ┗ 📜LSX_65_CAMARO_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂camaro concept
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CAMARO_CONCEPT.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂ccx
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CCX.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂Challenger 71
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHALLENGER71.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂challengern
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHALLENGER_CONCEPT.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂charger srt8
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHARGER06.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂charger69
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHARGER69.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂chevelle
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHEVELLE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂cobra 07
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_COBRA_07.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂corolla
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_COROLLA.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂eclipse
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_ECLIPSE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂europa s
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_EUROPAS.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂evo9
 ┃ ┃ ┃ ┃ ┃ ┗ 📜evo9_10k_rpm.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂ford gt
 ┃ ┃ ┃ ┃ ┃ ┗ 📜FORD_GT_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂g35
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_G35.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂gt3 rs (997)
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_997GT3RS.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂gt500
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_GT500.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂hemi cuda
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_HEMI_CUDA.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂jaguar xk
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_XK.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂mazda speed 3
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_MAZDASPEED3.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂mr2
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_MR2.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂r32
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_R32.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂roadrunner
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_ROADRUNNER.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂skyline r34
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_SKYLINE_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂sl65
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_SL65.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂slr
 ┃ ┃ ┃ ┃ ┃ ┗ 📜SLR_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┗ 📂zonda
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_ZONDA.nfsms
 ┃ ┃ ┃ ┣ 📂Most Wanted Cars
 ┃ ┃ ┃ ┃ ┣ 📂bmw m3 gtr mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BMW_M3_GTR_E46_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂carrera gt mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CARRERA_GT_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂Cayman s
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CAYMANS_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂Clio
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CLIO_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂clk500
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CLK500_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂corvette z06 mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CORVETTE_Z06_MW_SIMILAR_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂db9
 ┃ ┃ ┃ ┃ ┃ ┗ 📜DB9_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂eclipse gt
 ┃ ┃ ┃ ┃ ┃ ┗ 📜ECLIPSEGT_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂elise
 ┃ ┃ ┃ ┃ ┃ ┗ 📜ELISE_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂gallardo mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜GALLARDO_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂Gto mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_GTO.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂is300
 ┃ ┃ ┃ ┃ ┃ ┗ 📜IS300_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂lamborghini murcielago
 ┃ ┃ ┃ ┃ ┃ ┗ 📜MURCIELAGO&LP640_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂monaro
 ┃ ┃ ┃ ┃ ┃ ┗ 📜MONARO_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂mustang mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜MUSTANGGT_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂rx7 mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜RX7_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂rx8 mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜RX8_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂subaru impreza wrx carbon
 ┃ ┃ ┃ ┃ ┃ ┗ 📜IMPREZA_STI_MW.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂supra mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜SUPRA_STUTUTU.nfsms
 ┃ ┃ ┃ ┃ ┗ 📂viper
 ┃ ┃ ┃ ┃ ┃ ┗ 📜VIPER_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┗ 📜all in 1 (ovgi).nfsms
 ┃ ┃ ┗ 📂vlted
 ┃ ┃ ┃ ┣ 📂Carbon Cars
 ┃ ┃ ┃ ┃ ┣ 📂240sx
 ┃ ┃ ┃ ┃ ┃ ┗ 📜240SX_RB26_SWAP.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂300c
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_300C.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂350z
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_350Z.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂997tt
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_997TT.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂audi lemans
 ┃ ┃ ┃ ┃ ┃ ┗ 📜LEMANS_R8_BETTER_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂brera
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_BRERA.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂camaro 65
 ┃ ┃ ┃ ┃ ┃ ┗ 📜LSX_65_CAMARO_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂camaro concept
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CAMARO_CONCEPT.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂CCX
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CCX.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂Challenger 71
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHALLENGER71.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂challengern
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHALLENGER_CONCEPT.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂charger srt8
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHARGER06.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂charger69
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHARGER69.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂chevelle
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_CHEVELLE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂cobra 07
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_COBRA_07.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂corolla
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_COROLLA.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂eclipse
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_ECLIPSE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂europa s
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_EUROPAS.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂evo9
 ┃ ┃ ┃ ┃ ┃ ┗ 📜evo9_10k_rpm.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂ford gt
 ┃ ┃ ┃ ┃ ┃ ┗ 📜FORD_GT_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂g35
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_G35.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂gt3 rs (997)
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_997GT3RS.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂gt500
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_GT500.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂hemi cuda
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_HEMI_CUDA.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂jaguar xk
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_XK.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂mazda speed 3
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_MAZDASPEED3.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂mr2
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_MR2.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂r32
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_R32.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂roadrunner
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_ROADRUNNER.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂skyline r34
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_SKYLINE_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂sl65
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_SL65.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂slr
 ┃ ┃ ┃ ┃ ┃ ┗ 📜SLR_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┗ 📂zonda
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_ZONDA.nfsms
 ┃ ┃ ┃ ┣ 📂Most Wanted Cars
 ┃ ┃ ┃ ┃ ┣ 📂bmw m3 gtr mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BMW_M3_GTR_E46_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂carrera gt mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CARRERA_GT_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂Cayman s
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CAYMANS_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂Clio
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CLIO_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂clk500
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CLK500_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂corvette z06 mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CORVETTE_Z06_MW_SIMILAR_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂db9
 ┃ ┃ ┃ ┃ ┃ ┗ 📜DB9_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂eclipse gt
 ┃ ┃ ┃ ┃ ┃ ┗ 📜ECLIPSEGT_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂elise
 ┃ ┃ ┃ ┃ ┃ ┗ 📜ELISE_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂gallardo mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜GALLARDO_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂Gto mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜BETTER_GTO.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂is300
 ┃ ┃ ┃ ┃ ┃ ┗ 📜IS300_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂lamborghini murcielago
 ┃ ┃ ┃ ┃ ┃ ┗ 📜MURCIELAGO&LP640_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂monaro
 ┃ ┃ ┃ ┃ ┃ ┗ 📜MONARO_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂mustang mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜MUSTANGGT_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂rx7 mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜RX7_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂rx8 mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜RX8_MW_PERFORMACE.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂subaru impreza wrx carbon
 ┃ ┃ ┃ ┃ ┃ ┗ 📜IMPREZA_STI_MW.nfsms
 ┃ ┃ ┃ ┃ ┣ 📂supra mw
 ┃ ┃ ┃ ┃ ┃ ┗ 📜SUPRA_STUTUTU.nfsms
 ┃ ┃ ┃ ┃ ┗ 📂viper
 ┃ ┃ ┃ ┃ ┃ ┗ 📜VIPER_MW_PERFORMANCE.nfsms
 ┃ ┃ ┃ ┗ 📜all in 1 (vlted).nfsms
```
---

### Distribution Policy  

This mod has no distribution conditions. You are free to do whatever you want with it, but if you plan to use it as a base or in mod packs, you must give credit:
'Example: Based on Platanito22's mod [Nfs Carbon Performance Reworking], Modified by (your name)'

- **Allowed**:
- Mod packs and derivatives
- Redistributions with credit

---

### ⚠️ WARNING

Due to the nature of the mod, there are some bosses that become more competitive, if not difficult (especially in the canyon),
but it's more than anything, at the beginning and then everything will be more "relaxed", because I already went through it (in order to test my own mod) to see if the game
became unbearable or just becomes a little more complicated and my conclusion was that it is 'passable', the game does not become unplayable (I'm talking about the AI ​​and
the AI ​​of the bosses).

Another thing is that when you see the performance port of MW you will think, can it be used with the NFSC: MW'05 shiftpattern/ShiftSND Port https://nfsmods.xyz/mod/6237?, well
that I don't know for sure because I made the mod long before I even knew about the existence of that mod.

This mod is currently compatible with the Improvement Mod v2: https://nfsmods.xyz/mod/855, I haven't tried it with other mods like Ultimate, CBR or Endgame,
but I don't think it's totally incompatible with those mods as it's a performance improvement for the cars and doesn't touch any of the gameplay of those mods.

Finally, this mod ONLY MODIFIES THE CARS IN THE VANILLA GAME, this mod doesn't buff the performance of the Improvement Mod add-on cars
although if you want I can make a separate mod for that.

---

### Compatibility  

✅ Confirmed Working With:  

- [Improvement Mod v2](https://nfsmods.xyz/mod/855)  

❌ Untested/Unconfirmed:  

- Ultimate/CBR/Endgame Mods  
- [NFSC: MW'05 shiftpattern/ShiftSND Port](https://nfsmods.xyz/mod/6237)  

---

## ❓ FAQ

Q: Will you update this mod?
A: Just for bugs. Consider it feature complete.

Q: Can you make car version of Improvement Mod?
A: Possibly  

---

"Thanks for downloading! If you find any bugs, report it."
