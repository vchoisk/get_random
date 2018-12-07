# Riiid! 인터뷰

## 절차
Riiid는 지원자분의 역량과 fit을 효율적으로 파악하기 위하여, 상호적인 기술면접을 진행하고자 합니다.
주어진 시간까지 1차 작업을 하고 현 Riiid 개발자들의 feedback을 반영하여 최종적으로 작업을 하는 방식입니다.
면접과정을 통하여 지원자분 또한 Riiid 웹개발팀의 협업 과정에 대하여 알아가실수 있기 바랍니다.

1. 해당 Repo를 clone 한다.
```
$ git clone https://github.com/GITHUB_ID/REPOSITORY_NAME-GITHUB_ID.git
$ cd REPOSITORY_NAME-GITHUB_ID
```

2. 별도의 branch를 생성하여 작업한다.
```
$ git checkout -b BRANCH_NAME
$ git add/commit/push 
```

3. 1차 제출시 작업중인 branch를 master branch로 Pull Request(PR) 생성를 한다. 

4. Riiid 개발자들이 PR에 남긴 feedback을 반영하여 최종적으로 기술면접을 수정/제출한다.

# get_random

## 문제

`0`과 `1`을 랜덤으로 리턴하는 함수(`get_zero_or_one`)가 있습니다.
- 이 함수는 이미 있다고 가정합니다.
- Python으로 예를들면, random.randrange(2)를 사용해도 됩니다.

```

from random import randrange

get_zero_or_one = lambda: randrane(2)

```

위 함수를 이용하여 `0` 부터 `max_number - 1` 사이의 랜덤값을 리턴하는 함수(`get_random`)를
구현하시 면 됩니다.

```

def get_random(max_number):
  # Please implement this method
  # using only `get_zero_or_one`
  return 0

```

## 예제

실행 및 결과에 대한 예는 다음과 같습니다.

- 예 1
  1. 실행: `get_random(5)`
  2. 결과: `0` or `1` or `2` or `3` or `4`

- 예 2
  1. 실행: `get_random(3)`
  2. 결과: `0` or `1` or `2`

## 제약조건
- 프로그래밍 언어는 자유입니다.
- 위에서 언급한 함수(`get_zero_or_one` , `get_random`) 이외의 어떠한 의존성도 가질 수
없습니다.
  - 앞서 언급했듯 `get_zero_or_one` 의 내부에서 사용하신 함수는 예외입니다.