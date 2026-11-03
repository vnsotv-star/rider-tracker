# ແອັບບັນທຶກໄລເດີ (Capacitor → APK)

## ວິທີ A: ສ້າງ APK ໃນຄອມ (ຕ້ອງມີ Node.js 18+, JDK 17, Android Studio)
1. ແຕກໄຟລ໌ ZIP ແລ້ວເປີດ Terminal ໃນໂຟລເດີ
2. npm install
3. npx cap add android
4. npm run apk
5. ໄດ້ໄຟລ໌: android/app/build/outputs/apk/debug/app-debug.apk
6. ສົ່ງໄຟລ໌ເຂົ້າໂທລະສັບ ແລ້ວກົດຕິດຕັ້ງ (ເປີດ "ອະນຸຍາດຕິດຕັ້ງຈາກແຫຼ່ງທີ່ບໍ່ຮູ້ຈັກ")

ຫຼື: npx cap open android ເພື່ອເປີດໃນ Android Studio ແລ້ວກົດ Run ໃສ່ໂທລະສັບທີ່ຕໍ່ USB.

## ວິທີ B: ສ້າງ APK ໃນ GitHub (ບໍ່ຕ້ອງຕິດຕັ້ງຫຍັງ)
1. ສະໝັກ github.com ແລ້ວສ້າງ repository ໃໝ່ (ຊື່ຫຍັງກໍໄດ້)
2. ອັບໂຫຼດໄຟລ໌ທັງໝົດໃນ ZIP ນີ້ (ລວມໂຟລເດີ .github ແລະ www)
3. ໄປແຖບ Actions → Build APK → Run workflow
4. ລໍ 5-8 ນາທີ ແລ້ວດາວໂຫຼດ rider-tracker-apk ຈາກໜ້າ run
5. ແຕກ ZIP ໄດ້ app-debug.apk ແລ້ວຕິດຕັ້ງໃນໂທລະສັບ

## ແກ້ໄຂແອັບ
ແກ້ໄຟລ໌ www/index.html ແລ້ວ build ໃໝ່
