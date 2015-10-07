# ittekiter2015
## Git-Flowモデル
1. **master** 	
 動作可能版。テストが完了したdevelopブランチを移行する。masterブランチにはコミットしない。
 保護ブランチで*プッシュ不可能、マージリクエストのみ可能*。
2. **develop**	
 featureブランチをマージしてテストを行う。
3. **feature**	
 機能の開発やバグフィックスを行う。機能毎に随時作成・統合・破棄する。ブランチ名は*feature/○○*とする。
4. **hotfix**	
 緊急バグ対応用。masterブランチから分岐し、masterとdevelopにマージして、バグを修正する。
5. **release**	
 公開版管理用。公開していないので使用予定なし。
