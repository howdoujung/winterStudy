# winterStudy

2주차 실습 중 a를 올린 뒤 b를 올리는 과정에서 이상함을 느껴 c 파일을 만들어 봤고
멀쩡하게 올라가던 a와 달리 안 올라갔다. 결국 아예 다 삭제하고 config부터 다시 설정해주었다.

<오류>

 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/howdoujung/winterStudy.git'

git push origin master 명령어를 입력하면 나오는 오류로 구글링을 해보니 깃허브에 내 로컬에 없는 파일이
있고, 내 파일을 push 하면 발생하는 오류라고 한다. update를 하고 push를 하면 해결된다고 한다.
update방법은 pull을 하고 push를 하면 된다.

처음엔 git pull origin master을 통해 해결하고 싶었으나 잘 해결되지 않았다.
결국 강제 명령어인 git push -u origin +master을 이용하여 해결했다.
