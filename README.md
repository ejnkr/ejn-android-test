# EJN 안드로이드 개발자 채용 과제를 위한 프로젝트 입니다.
## 목적
- 안드로이드 개발에는 다양한 방법이 있습니다.
- 지원해주신 여러분의 개발 방법을 파악해서 저희와 같은 방향으로 함께 성장할 수 있을지 참고하고자 합니다.

## 목표
- 이 저장소를 fork 하고 아래 api를 통해 결과를 가져와 샘플과 비슷한 화면을 구성 합니다.
<pre><code>https://developers.themoviedb.org/3/movies/get-popular-movies</code></pre>
- Api key는 아래에 있는 파일의 값을 사용해주세요.
<pre><code>/key.properties > tmdb_api_key</pre></code>
- 비슷한 화면이라 함은 1px, 1dp 중요하지 않습니다. 화면에는 "썸네일 이미지", "제목"만 있으면 됩니다.
- 어떤 라이브러리를 사용해도 좋습니다.
- SwipeRefreshLayout, RecyclerView를 사용하고 infiniteScroll (lazy loading)을 구현해주세요.

## 이런 부분이 있으면 좋아요.
- kotlin dsl 을 사용하면 좋아요.
- MVVM 패턴에 가까운 설계를 하면 좋아요. (ViewModel, DataBinding, LiveData)
- RxJava를 사용하면 좋아요.
- 이미지 라이브러리는 Glide, 네트워크 라이브러리는 Retrofit2 를 사용하면 좋아요.
- 코드를 작성하면서 고민되는 부분이 있다면 자유롭게 README 에 적어주세요.

## 샘플 스크린샷
![sample img](/img_sample.png)
