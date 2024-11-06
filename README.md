# AmazonCloudWatchAlarm_remind-Notification
cloudwatch_remind.yamlをダウンロードしてお使いください。

# パラメータ補足
AWSAccountID
→AWSのアカウントIDの12桁の数字を入力

CloudWatchAlarmArn
→繰り返し通知させたいCloudWatchAlarmのARN

CloudWatchAlarmName
→繰り返し通知させたいCloudWatchAlarmのアラーム名

RegionName
→デプロイしたいリージョンID(東京Rの場合はap-northeast-1)

SNSTopicArn
→メールを飛ばしたいSNSトピックのARN


# コードの補足
encoded_alarm_nameはアラーム名に日本語が入っている場合を想定して入れています。

アラーム名が英文の場合でも、そのまま使用できます。
