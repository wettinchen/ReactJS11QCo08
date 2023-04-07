## ReactJS Chapter 11
It is my coding practice with the TUTORIAL of Dave Gray. 

## Source
### Dave Gray 的 Reactjs 課程
https://youtube.com/playlist?list=PL0Zuz27SZ-6PrE9srvEn8nbhOOyxnWXfp
### Dave Gray 的 YouTube 頻道
https://www.youtube.com/@DaveGrayTeachesCode

## ReactJS Chapter 11
   Quick Concept outline
   中文摘要說明與重點提問
   
###  1. Intro 
        教學影片固定的開頭和摘要說明

###  2. Set up
        設定

###  3. useEffect hook with no dependencies <Code更動>
        匯入 useEffect 並使用 useEffect

###  4. useEffect hook at app load <Code更動>
        設定一個 空的 Array 為 dependency，表示在 app 只會在這個時候載入

###  5. useEffect hook only when a dependency changes <Code更動>
        在 Array 加入 items，觀察列表更新的變動。

###  6. useEffect is not synchronous <Code更動>
        用一個在 useEffect 前和一個在 useEffect 後的 console.log，
        說明 useEffect不具同步性。
        在 Search Item 輸入文字，觀察對話框重新呈現的結果。

###  7. Loading data with useEffect <Code更動>
        用 useEffect 載入資料
       
###  8. Avoid this BIG mistake with useEffect <Code更動>
        避免無止盡的迴圈

###  9. Avoiding a loading error with useState <Code更動>
        避免列表因為沒有項目而導致載入錯誤。

### 10. Saving data with useEffect <Code更動>
        用 useEffect 儲存資料


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
