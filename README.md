부트스트랩을 활용한 리액트 페이지 제작 및 배포

 1. create-react-app doglist
 2. npm install bootstrap
 3. npm start
 4. doglist>npm install gh-pages --save-dev
 5. package.json "scripts" 아래에 "predeploy": "npm run build",
                                  "deploy": "gh-pages -d build" 추가
 6. package.json 맨 아래에 "homepage":https://sungjong96.github.io/doglist/", 추가
 7. npm run deploy
 8. github doglist 에서 setting > pages > branch : main 으로 변경 후 save
 9. repositiries 설정 > url 등록
