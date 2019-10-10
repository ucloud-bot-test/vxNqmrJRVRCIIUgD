
# 错误码
| Http状态码  | Message                     | 错误说明                               |
|---|---|---|
| 43000    | ConnectDBError              | 内部错误                               |
| 43001    | GetDBConfigError            | 内部错误                               |
| 43002    | DBFindError                 | 内部错误                               |
| 43003    | DBUpateError                | 内部错误                               |
| 43004    | TokenNotVaild               | 无效的Token，身份验证失败，请重新获取Token         |
| 43005    | TokenExpired                | Token过期，身份验证失败，请重新获取Token          |
| 43006    | ParaMiss                    | 参数错误或确认必要参数                        |
| 43007    | ReadReqError                | 内部错误                               |
| 43008    | SubmitTaskFail              | 内部错误                               |
| 43009    | WriteStdOutToTarError       | 内部错误                               |
| 43010    | WriteStdErrToTarError       | 内部错误                               |
| 43011    | WriteFileToTarError         | 内部错误                               |
| 43012    | WriteResError               | 内部错误                               |
| 43013    | JsonMarshalError            | 内部错误                               |
| 43014    | JsonUnMarshaError           | 内部错误                               |
| 43015    | DescribeTaskFail            | 内部错误                               |
| 43016    | TaskNotFound                | 找不到指定的任务，TaskId错误                  |
| 43017    | TaskInfoError               | 内部错误                               |
| 43018    | InnerFrameworkError         | 内部错误                               |
| 43019    | SendImageReqFail            | 内部错误                               |
| 43020    | SendImageReqTimeout         | 内部错误                               |
| 43021    | ReadImageResError           | 内部错误                               |
| 43022    | CreateBucketConflict        | 镜像仓库名重复，bucket名称全局唯一               |
| 43023    | BucketNotExistError         | 指定的镜像仓库不存在或请求失败                    |
| 43024    | ImageNameNotValid           | 非法的镜像名，镜像名称必须是英文或数字                |
| 43025    | BucketNameNotValid          | 镜像仓库名称不合法，可以是小写字母、数字、下划线，长度限制4~30  |
| 43026    | ActionNameNotValid          | Action名称错误                         |
| 43027    | ApiAccountNotValid          | 请求地址错误，请从api.ucloud.cn调用此接口        |
| 43028    | TimeParamNotValid           | 时间参数错误，不能为空                        |
| 43029    | CostThresholdNotValid       | 耗时阈值错误                             |
| 43030    | RedisConfNotValid           | Redis配置错误                          |
| 43031    | GetRedisInstanceError       | 连接Redis失败                          |
| 43032    | GetTaskIdInRangeError       | 获取任务Id失败                           |
| 43033    | ParaError                   | 参数错误，请检查输入参数                       |
| 43037    | DelAppContainerFail         | 删除App容器失败                          |
| 43038    | DelAppContainerPartSuccess  | 删除App容器部分成功                        |
| 43039    | StopTaskFail                | 停止任务失败                             |
| 43040    | StartAppContainerFail       | 开始App容器失败                          |
| 43041    | DecreaseAppContainerFail    | 缩容实例失败                             |
| 43042    | ListAppContainerFail        | 获取实例详情失败                           |
| 43043    | SendDeleteImageReqFail      | 删除镜像请求失败                           |
| 43044    | SendDeleteImageReqTimeout   | 删除镜像请求超时                           |
| 43045    | DeleteImageNotExsitError    | 被删除镜像不存在，请检查镜像名称                   |
| 43046    | DeleteImageEmptyError       | 被删除镜像不能为空                          |
| 43047    | DeleteTagNameEmptyError     | 被删除Tag不能为空                         |
| 43048    | SubmitTaskContainerError    | 用户传入参数错误，导致容器内部运行错误                |
