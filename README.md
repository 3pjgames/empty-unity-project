# 用法 #

-   在 Gitlab 里新建项目，以 `wu/wu_client`，拷贝 git clone 地址，比如 `git@gitlab.3pjgames.com:wu/wu_client.git`。
-   Clone 本项目，并 push 到新的项目中做为新项目模板

        # clone 本项目，已经克隆可省略这一步
	    git clone git@gitlab.3pjgames.com:3pjgames/unity-blank.git
	    # 切换到本项目根目录中
	    cd unit-blank
	    # 检查更新
	    git pull
	    # 将 wu_client 的 git 地址作为名为 wu_client 的 remote
	    git remote add wu_client git@gitlab.3pjgames.com:wu/wu_client.git
	    # 将本项目的代码推送到 wu_client 中
	    git push wu_client master:master
	
-    将新项目 clone 到本地

        git clone git@gitlab.3pjgames.com:wu/wu_client.git
	    