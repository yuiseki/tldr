# typeset

> 변수를 선언하고 속성을 부여합니다.
> 더 많은 정보: <https://www.gnu.org/software/bash/manual/bash.html#Bash-Builtins>.

- 지정된 값으로 문자열 변수 선언:

`typeset {{변수}}="{{값}}"`

- 지정된 값으로 정수 변수 선언:

`typeset -i {{변수}}="{{값}}"`

- 지정된 값으로 배열 변수 선언:

`typeset {{변수}}=({{항목_a 항목_b 항목_c}})`

- 지정된 값으로 연관 배열 변수 선언:

`typeset -A {{변수}}=({{[키_a]=항목_a [키_b]=항목_b [키_c]=항목_c}})`

- 지정된 값으로 읽기 전용 변수 선언:

`typeset -r {{변수}}="{{값}}"`

- 함수 내에서 지정된 값으로 전역 변수 선언:

`typeset -g {{변수}}="{{값}}"`
