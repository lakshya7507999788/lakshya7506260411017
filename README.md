git clone https://github.com/आपका-उपयोगकर्ता-नाम/आपका-प्रोजेक्ट.git
cd आपका-प्रोजेक्ट
npm install
npx cap add android
# या iOS के लिए (केवल Mac पर):
# npx cap add ios
npm run build
npx cap sync
npx cap run android
# या iOS के लिए:
# npx cap run ios
