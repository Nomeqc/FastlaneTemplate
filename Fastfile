import_from_git(url: 'https://github.com/Nomeqc/GeneralFastfile.git',
               path: './GeneralFastfile')

default_platform :ios

platform :ios do
  desc "Deploy a new version to beta "
  lane :beta do
    task(type: "adhoc")
  end


  desc "Deploy a new version to the App Store"
  lane :release do
    task(type: "appstore")
  end

 after_all do |lane|
    # This block is called, only if the executed lane was successful

    # slack(
    #   message: "Successfully deployed new App Update."
    # )
    send_message_to_dingtalk(message: "大吉大利，晚上吃鸡🐔")
 end

 error do |lane, exception|
    # slack(
    #   message: exception.message,
    #   success: false
    # )
    send_message_to_dingtalk(message: exception.message)
 end

end