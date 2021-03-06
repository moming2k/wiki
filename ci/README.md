Continuous Integration
======================

CI 的特色

* 維護一個獨立的程式碼管理區
* 自動化建置
* 可以自動化測試
* 每個開發人員可以每天將程式提交到一個主要地方
* 這些提交的程式碼可以在一個獨立整合幾器上面建置
* 讓它可以建置快速
* 可以複製在產品環境下測試
* 可以讓任何一個開發人簡單的取得最新可以執行的程式
* 每一個人可以看到自動化測試的結果

CI 是一種概念，也是驅動所有系統品質工具的引擎

* 有了 CI ，不懂技術的管理者，可以光看報表就知道系統的健康狀況。
* 有了 CI ，團隊開發時可以及早發現，在整合上是否有所問題。
* 有了 CI ，每個developer早點嗅出程式與系統的壞味道。
* 有了 CI ，可以讓整個團隊成員有共同的基底、共同的標準、共同協同合作的平台。
* 有了 CI ，可以貫穿整個系統開發生命週期，為了品質所花的任何一份力氣，都不會白費而有所累積。

CI 是一層品質的防護網，這層防護網是將其他每個維持品質的工具組織起來，整合起來，不斷不斷的持續整合，並即時產生回饋給所有成員。

Practice
--------

以下參考 Teddy 的文章

* [開發人員應遵循的七項持續整合要領](http://teddy-chen-tw.blogspot.tw/2012/07/blog-post.html)
* [持續整合工程師應遵循的十項要領（上）](http://teddy-chen-tw.blogspot.tw/2012/07/blog-post_04.html)
* [持續整合工程師應遵循的十項要領（下）](http://teddy-chen-tw.blogspot.tw/2012/07/blog-post_05.html)

Developer 應該了解的要點

1. Commit code frequently
2. Don’t commit broken code
3. Fix broken builds immediately
4. Write automated developers tests
5. All tests and inspections must pass
6. Run private builds
7. Avoid getting broken code

CI Engineer 應該了解的要點

1. Automate builds
2. Perform single command builds
3. Separate build scripts from your IDE
4. Centralize software assets
5. Create a consistent directory structure
6. Fail builds fast
7. Build for any environment
8. Use a dedicated CI machine and a CI server
9. Run fast builds
10. State builds

Implements
----------

* [GitLab CI](gitlab-ci.md)
* [Jenkins CI](http://jenkins-ci.org/)
* [Circle CI](https://circleci.com/)
* [Travis CI](https://travis-ci.org/) SaaS 服務
* [Drone.io](https://drone.io/)
* [TeamCity](https://www.jetbrains.com/teamcity/) (JetBrains 家出的 CI)
* [Bamboo](https://www.atlassian.com/software/bamboo) (Atlassian 家出的 CI)
* [PHPCI](https://www.phptesting.org/)
* [Codeship](https://codeship.com/) SaaS 服務，跟 [AWS](/cloud-computing/aws/README.md) 整合良好

其他好用的工具

* [Shields.io](http://shields.io/) - 用圖表示目前專案的健康度

Reference
---------

* [漫談持續整合](http://kojenchieh.pixnet.net/blog/post/378400769)
* [持續整合所需準備事項](http://kojenchieh.pixnet.net/blog/post/378870311)
* [執行持續整合所需要的紀律](http://kojenchieh.pixnet.net/blog/post/379112090)
* [十件有關CI的事情](http://kojenchieh.pixnet.net/blog/post/75411763)
* [內修敏捷開發心法 + 外練持續整合招式](https://blog.toright.com/posts/4139)
* [Git Workflows and Continuous Delivery](http://blogs.wandisco.com/2013/07/24/git-workflows-and-continuous-delivery-using-multisite-replication-to-facilitate-a-global-mainline/)
