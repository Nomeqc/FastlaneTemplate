###################### More Options ######################
# If you want to have even more control, check out the documentation
# https://docs.fastlane.tools/actions/deliver


###################### Automatically generated ######################
# Feel free to remove the following line if you use fastlane (which you should)
#require 'dotenv/load'


# Apple ID
# username ENV['APPLE_ID'] # your Apple ID user

# Bundle Id
# app_identifier ENV['APP_IDENTIFIER'] # The bundle identifier of your app

# 是否跳过HTML 报告验证？
force true

# 是否跳过上传二进制包？
skip_binary_upload ENV['SKIP_BINARY_UPLOAD']

# 是否跳过上传屏幕截图？
skip_screenshots ENV['SKIP_SCREENSHOTS']

# 是否跳过上传元数据？
skip_metadata ENV['SKIP_METADATA']

# 是否预先检查app内购？
precheck_include_in_app_purchases false

# 元数据路径
metadata_path ENV['METADATA_PATH']

# 截屏路径
screenshots_path ENV['SCREENSHOTS_PATH']

# 分级
app_rating_config_path "./fastlane/app_rating.json"

# app 定价
price_tier 0

# 是否提交审核？
submit_for_review ENV['SUBMIT_REVIEW']

submission_information({
              content_rights_contains_third_party_content: true, #是否包含第三方内容
              content_rights_has_rights: true, #是否拥有版权
              export_compliance_uses_encryption: false, #是否使用加密功能 (首次提交需要填写此选项)
              export_compliance_encryption_updated: false, # 自上次提交后您是否为此 App 添加或更改了加密功能？(非第一次提交审核需要此选项)
              add_id_info_uses_idfa: false #是否使用idfa
              })

# 审核通过后自动发布？
automatic_release true

