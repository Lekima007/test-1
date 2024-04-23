[master 075a718] merge 0.4
david@DavidsMBP git-test01 % git switch 0.4
切换到分支 '0.4'
david@DavidsMBP git-test01 % git switch master
切换到分支 'master'
david@DavidsMBP git-test01 % git switch 0.3
切换到分支 '0.3'
david@DavidsMBP git-test01 % git add .
david@DavidsMBP git-test01 % git commit -m '0.3-second-6 line'
[0.3 41c5b24] 0.3-second-6 line
 1 file changed, 6 insertions(+), 1 deletion(-)
david@DavidsMBP git-test01 % git switch master
切换到分支 'master'
david@DavidsMBP git-test01 % git merge 0.3
自动合并 test.txt
冲突（内容）：合并冲突于 test.txt
自动合并失败，修正冲突然后提交修正的结果。
david@DavidsMBP git-test01 % git merge 0.3
致命错误：您尚未结束您的合并（存在 MERGE_HEAD）。
请在合并前先提交您的修改。
david@DavidsMBP git-test01 % git switch 0.3
错误：您对下列文件的本地修改将被检出操作覆盖：
        test.txt
请在切换分支前提交或贮藏您的修改。
正在终止