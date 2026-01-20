## v2.2.0

Changes since v2.1.2:
* Merge pull request #149 from Hybrid-Mount/dev
* fix(webui): sync config field name 'backup' with backend expectations
* fix(store): improve error handling and remove redundant comments
* refactor(webui): localize error messages and fix TS interface gaps
* fix: config tab save
* feat(ui): refactor language selector to use md-dialog
* New Crowdin translations by GitHub Action (#143)
* workflow: add schedule trigger
* fix: 更新语言设置为 en-US，添加本地化文件和描述
* New Crowdin translations by GitHub Action (#142)
* delete: 移除多个语言本地化文件
* delete: 移除丹麦语本地化文件
* fix: 更新推送路径以包含所有本地化文件
* Update Vietnamese localization and remove Hong Kong Chinese localization
* New Crowdin translations by GitHub Action (#140)
* refactor: 移除冗余的冲突检查相关文本以简化本地化文件
* fix: 修正GITHUB_TOKEN环境变量引用以确保Crowdin集成正常工作
* refactor: 移除冗余的配置项和日志部分以简化本地化文件
* chore: 添加GITHUB_TOKEN环境变量以支持Crowdin集成
* Add localization support for multiple languages and configure Crowdin integration
* feat: 修改本地化文件命名以适应Crowdin
* Refactor: config loading and unify conflict/diagnostic analysis
* docs: update README and README_ZH to improve clarity and consistency in module descriptions and features
* chore: format code and ensure consistent newline at end of files
* fix: resolve eslint errors
* chore: remove unused code, improve type safety, and enhance error handling across multiple components
* refactor: Clean up code formatting and improve readability in ModulesTab and StatusTab components
* fix: simplify overlay xattr support check logic
* chore: cleanup useless code
* fix: remove unused overlay test xattr and improve error handling in xattr support check
* chore: update license headers [skip ci]
* fix: optimize overlay xattr support check for Linux and Android
* feat: update backup terminology and functionality in CLI handlers
* Refactor: Unify terminology, improve safety, and fix logic issues
* fix: remove unused NukeExt4Sysfs import from try_umount.rs
* chore: bump ndk to r29
* ci: change new ci way
* fix: make clippy happy
* fix: resolve compilation errors by removing nuke_active from core logic and state
* chore: remove nuke and dry-run features
* chore(release): bump version to v2.1.2 [skip ci]