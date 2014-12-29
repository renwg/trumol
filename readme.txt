1銆亀indows骞冲彴涓嬭浇鍦板潃
   http://msysgit.github.io/

2銆佸畨瑁呭畬鎴愬悗锛岃繕闇€瑕佹渶鍚庝竴姝ヨ缃紝鍦ㄥ懡浠よ杈撳叆锛?
   $ git config --global user.name "projectName"
   $ git config --global user.email "email@email.com"

   //鍥犱负Git鏄垎甯冨紡鐗堟湰鎺у埗绯荤粺锛屾墍浠ワ紝姣忎釜鏈哄櫒閮藉繀椤昏嚜鎶ュ闂細浣犵殑鍚嶅瓧鍜孍mail鍦板潃銆?
   //git config鍛戒护鐨?-global鍙傛暟锛岀敤浜嗚繖涓弬鏁帮紝琛ㄧず浣犺繖鍙版満鍣ㄤ笂鎵€鏈夌殑Git浠撳簱閮戒細浣跨敤杩欎釜閰嶇疆锛?

3銆佸垱寤虹増鏈簱
   3.1 绗竴姝ワ紝閫夋嫨涓€涓悎閫傜殑鍦版柟锛屽垱寤轰竴涓┖鐩綍锛?
   $ mkdir E:/repository
   $ cd E:/repository
   $ pwd
    E/repository

   3.2 绗簩姝ワ紝閫氳繃git init鍛戒护鎶婅繖涓洰褰曞彉鎴怗it鍙互绠＄悊鐨勪粨搴擄細
   $ git init

4銆佹妸涓€涓枃浠舵斁鍒癎it浠撳簱鍙渶瑕佷袱姝ャ€?
   4.1 绗竴姝ワ紝鐢ㄥ懡浠it add鍛婅瘔Git锛屾妸鏂囦欢娣诲姞鍒颁粨搴擄細
   $ git add readme.txt

   4.2 绗簩姝ワ紝鐢ㄥ懡浠it commit鍛婅瘔Git锛屾妸鏂囦欢鎻愪氦鍒颁粨搴擄細
   $ git commit -m "wrote a readme file"

5銆佽繍琛実it status鍛戒护鐪嬬湅缁撴灉

6銆佹煡鐪嬪巻鍙茶褰?
   鍦℅it涓紝鎴戜滑鐢╣it log鍛戒护鏌ョ湅锛?
   $ git log --pretty=oneline

7銆佺増鏈洖閫€
   鎴戜滑瑕佹妸褰撳墠鐗堟湰鈥渁ppend GPL鈥濆洖閫€鍒颁笂涓€涓増鏈€渁dd distributed鈥濓紝灏卞彲浠ヤ娇鐢╣it reset鍛戒护锛?
   鍦℅it涓紝鐢℉EAD琛ㄧず褰撳墠鐗堟湰,
   涓婁竴涓増鏈氨鏄疕EAD^锛屼笂涓婁竴涓増鏈氨鏄疕EAD^^锛屽綋鐒跺線涓?00涓増鏈啓100涓猑姣旇緝瀹规槗鏁颁笉杩囨潵锛屾墍浠ュ啓鎴怘EAD~100
   $ git reset --hard HEAD^

8銆佹仮澶嶅埌鎸囧畾鐗堟湰 git reset --hard commit_id
   $ git reset --hard cb926e7

9銆佺敤git reflog鏌ョ湅鍛戒护鍘嗗彶锛屼互渚跨‘瀹氳鍥炲埌鏈潵鐨勫摢涓増鏈€?
   $ git reflog

10銆佺敤git log鍙互鏌ョ湅鎻愪氦鍘嗗彶锛屼互渚跨‘瀹氳鍥為€€鍒板摢涓増鏈€?
   $ git log --pretty=oneline
  

asdfasdf

asdfasdf
asdf

OK
Why?
asdf


asdf


asdf


ew
w
e
we
we
we
we
we

we
rw
er
w
erw
er
Creating a new branch is quick AND simple.