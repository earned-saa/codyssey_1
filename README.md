soobiniro1987@c1r6s1 codyssey_1 % git status
현재 브랜치 main
브랜치가 'origin/main'에 맞게 업데이트된 상태입니다.

커밋하도록 정하지 않은 변경 사항:
  (무엇을 커밋할지 바꾸려면 "git add <파일>..."을 사용하십시오)
  (use "git restore <file>..." to discard changes in working directory)
        수정함:        README.md

커밋할 변경 사항을 추가하지 않았습니다 ("git add" 및/또는 "git commit -a"를
사용하십시오)
soobiniro1987@c1r6s1 codyssey_1 % gid add
zsh: command not found: gid
soobiniro1987@c1r6s1 codyssey_1 % git add README.md 
soobiniro1987@c1r6s1 codyssey_1 % git status
현재 브랜치 main
브랜치가 'origin/main'에 맞게 업데이트된 상태입니다.

커밋할 변경 사항:
  (use "git restore --staged <file>..." to unstage)
        수정함:        README.md

soobiniro1987@c1r6s1 codyssey_1 % git commit -m "mission files"
[main 309982f] mission files
 Committer: 정수빈 <soobiniro1987@c1r6s1.codyssey.kr>
이름과 전자메일 주소를 사용자 이름과 호스트 이름을 이용해서 자동으로
설정했습니다. 이 정보가 맞는지 확인하십시오. 이 메시지를 보지 않으려면 정보를
명시적으로 설정하십시오. 다음 명령어를 실행하고 편집기의 안내에 따라 설정
파일을 편집하십시오:

    git config --global --edit

이렇게 한 다음, 이 커밋에 사용한 신원 정보를 다음과 같이 해서 바꿀 수 있습니다:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+), 1 deletion(-)
soobiniro1987@c1r6s1 codyssey_1 % git push
오브젝트 나열하는 중: 5, 완료.
오브젝트 개수 세는 중: 100% (5/5), 완료.
Delta compression using up to 6 threads
오브젝트 압축하는 중: 100% (2/2), 완료.
오브젝트 쓰는 중: 100% (3/3), 284 bytes | 284.00 KiB/s, 완료.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/earned-saa/codyssey_1.git
   e94824d..309982f  main -> main
soobiniro1987@c1r6s1 codyssey_1 % 
