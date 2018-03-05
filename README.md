# 한발 먼저 가본 문과생이 알려주는, 데이터 시각화 - 아무것도 모르고 react 시작하기



이 Repository는 '한발 먼저 가본 문과생이 알려주는, 데이터 시각화 - 아무것도 모르고 react 시작하기'의 예제 파일입니다. https://github.com/rafrex/spa-github-pages 을 많이 변경하지 않고 아티클만큼 구현된 repository입니다.
 이 코드들과 자신의 코드를 비교해봐도 좋고 clone하여 수정해봐도 좋은 방법입니다.

#### Clone하여 사용하기
1. Clone하기 ($ git clone https://github.com/oneybee/reactapp.git)

2. 자신의 repository로 바꿔주기
  
    $ cd reactapp

    $ rm -rf .git

    $ git init

    $ git add .

    $ git commit -m '버전이름'

    $ git branch -m gh-pages 

    $ git remote add origin <repository url>

3. repository basename 지정해주기
    텍스트 에디터를 이용해 /Src/index.js로 이동
   
    ReactDOM.render(
    <BrowserRouter basename="/reactapp">

    "/reactapp" => "/repository 이름"  으로 변경해주기

4. index.html에서 
    <script src="/reactapp/build/bundle.js"></script> 부분을
    "/build/bundle/js" => "/repositoryname/build/bundle.js" 로 변경해주기

5. $ npm instal

   $ npm run build

6. add -> commit -> push 진행하기




<!-- links to within repo -->
[404html]: https://github.com/rafrex/spa-github-pages/blob/gh-pages/404.html
[segmentCount]: https://github.com/rafrex/spa-github-pages/blob/gh-pages/404.html#L26
[indexHtmlScript]: https://github.com/rafrex/spa-github-pages/blob/gh-pages/index.html#L58
[indexHtmlSPA]: https://github.com/rafrex/spa-github-pages/blob/gh-pages/index.html#L94
[cnameFile]: https://github.com/rafrex/spa-github-pages/blob/gh-pages/CNAME
[indexHtmlTitle]: https://github.com/rafrex/spa-github-pages/blob/gh-pages/index.html#L6
[404htmlTitle]: https://github.com/rafrex/spa-github-pages/blob/gh-pages/404.html#L5
[favicon]: https://github.com/rafrex/spa-github-pages/blob/gh-pages/index.html#L34
[startScript]: https://github.com/rafrex/spa-github-pages/blob/gh-pages/package.json#L6

<!-- links to github docs -->
[ghPagesOverview]: https://pages.github.com/
[ghPagesBasics]: https://help.github.com/categories/github-pages-basics/
[ghPagesTypes]: https://help.github.com/articles/user-organization-and-project-pages/
[customDomain]: https://help.github.com/articles/quick-start-setting-up-a-custom-domain/
[nojekyll]: https://help.github.com/articles/files-that-start-with-an-underscore-are-missing/

<!-- other links -->
[liveExample]: http://spa-github-pages.rafrex.com
[react]: https://github.com/facebook/react
[reactRouter]: https://github.com/ReactTraining/react-router
[seoLand]: http://searchengineland.com/tested-googlebot-crawls-javascript-heres-learned-220157
[webpackProduction]: https://webpack.js.org/guides/production-build/#the-automatic-way
[webpackDevtool]: https://webpack.js.org/configuration/devtool/
[reactInteractive]: https://github.com/rafrex/react-interactive
[formspree]: http://formspree.io/
