# SICP 릴레이 문제 풀이

## 멤버

## 문제 풀고 올리는 방법

1. leiningen 설치
```bash
brew install leiningen
```

2. 프로젝트 clone 
```
git clone https://github.com/eunmin/sicp.git
```

3. 문제 풀어서 올리는 방법 

- `연습문제 1.1`를 푼다고 하면 `src/sicp/ex_1_1.clj` 파일을 만들고 아래와 같은 형식으로 파일을 작성합니다.

```clojure
(ns sicp.ex-1-1)

(def 문제
  "두 숫자를 인자로 받아 두 값을 덧셈하여 내놓는 프로시저를 정의하라.")

;; 아래에 자유롭게 연습 문제 코드를 작성합니다.
(defn add [x y]
  (+ x y))
```

- 파일명은 _이고 `ns` 옆에 붙는 것은 - 인 것에 주의하세요.

4. 문제 실행해 보기

- 프로젝트 최상위 폴더에서 아래와 같이 명령어를 입력해 REPL을 실행합니다.
```bash
lein repl
```

- 내가 작성한 연습문제를 로딩합니다.
```bash
user=> (ns sicp.ex-1-1)
sicp.ex-1-1=> (load "ex_1_1")
sicp.ex-1-1=> (add 1 2)
3
sicp.ex-1-1=> 
```

- 파일을 고치고 다시 실행하려면 다시 로드 합니다.
```bash
sicp.ex-1-1=> (load "ex_1_1")
sicp.ex-1-1=> (add3 1 2)
6
sicp.ex-1-1=> 
```







