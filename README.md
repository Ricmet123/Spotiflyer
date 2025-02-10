# Spotiflyer
Spotiflyer not working 
DownloadLinkFetchFailed(errorTrace=Find Link for Bobjan 

Fetching From Saavn Failed:DownloadLinkFetchFailed(errorTrace=No SAAVN Match Found for Bobjan)
	at com.shabinder.common.providers.saavn.requests.JioSaavnRequests$DefaultImpls.findBestSongDownloadURL(JioSaavnRequests.kt:299)
	at com.shabinder.common.providers.saavn.requests.JioSaavnRequests$findBestSongDownloadURL$1.invokeSuspend(Unknown Source:10)
	at h7.a.resumeWith(ContinuationImpl.kt:10)
	at io.ktor.util.pipeline.SuspendFunctionGun.resumeRootWith(SuspendFunctionGun.kt:55)
	at io.ktor.util.pipeline.SuspendFunctionGun.loop(SuspendFunctionGun.kt:17)
	at io.ktor.util.pipeline.SuspendFunctionGun.access$loop(SuspendFunctionGun.kt:0)
	at io.ktor.util.pipeline.SuspendFunctionGun$continuation$1.resumeWith(SuspendFunctionGun.kt:24)
	at h7.a.resumeWith(ContinuationImpl.kt:33)
	at io.ktor.util.pipeline.SuspendFunctionGun.resumeRootWith(SuspendFunctionGun.kt:55)
	at io.ktor.util.pipeline.SuspendFunctionGun.loop(SuspendFunctionGun.kt:17)
	at io.ktor.util.pipeline.SuspendFunctionGun.access$loop(SuspendFunctionGun.kt:0)
	at io.ktor.util.pipeline.SuspendFunctionGun$continuation$1.resumeWith(SuspendFunctionGun.kt:24)
	at h7.a.resumeWith(ContinuationImpl.kt:33)
	at io.ktor.util.pipeline.SuspendFunctionGun.resumeRootWith(SuspendFunctionGun.kt:55)
	at io.ktor.util.pipeline.SuspendFunctionGun.loop(SuspendFunctionGun.kt:17)
	at io.ktor.util.pipeline.SuspendFunctionGun.access$loop(SuspendFunctionGun.kt:0)
	at io.ktor.util.pipeline.SuspendFunctionGun$continuation$1.resumeWith(SuspendFunctionGun.kt:24)
	at h7.a.resumeWith(ContinuationImpl.kt:33)
	at io.ktor.util.pipeline.SuspendFunctionGun.resumeRootWith(SuspendFunctionGun.kt:55)
	at io.ktor.util.pipeline.SuspendFunctionGun.loop(SuspendFunctionGun.kt:17)
	at io.ktor.util.pipeline.SuspendFunctionGun.access$loop(SuspendFunctionGun.kt:0)
	at io.ktor.util.pipeline.SuspendFunctionGun$continuation$1.resumeWith(SuspendFunctionGun.kt:24)
	at h7.a.resumeWith(ContinuationImpl.kt:33)
	at io.ktor.util.pipeline.SuspendFunctionGun.resumeRootWith(SuspendFunctionGun.kt:55)
	at io.ktor.util.pipeline.SuspendFunctionGun.loop(SuspendFunctionGun.kt:17)
	at io.ktor.util.pipeline.SuspendFunctionGun.access$loop(SuspendFunctionGun.kt:0)
	at io.ktor.util.pipeline.SuspendFunctionGun$continuation$1.resumeWith(SuspendFunctionGun.kt:24)
	at h7.a.resumeWith(ContinuationImpl.kt:33)
	at kotlinx.coroutines.DispatchedTask.run(DispatchedTask.kt:100)
	at kotlinx.coroutines.internal.LimitedDispatcher.run(LimitedDispatcher.kt:12)
	at kotlinx.coroutines.scheduling.TaskImpl.run(Tasks.kt:2)
	at kotlinx.coroutines.scheduling.CoroutineScheduler.runSafely(CoroutineScheduler.kt:0)
	at kotlinx.coroutines.scheduling.CoroutineScheduler$Worker.executeTask(CoroutineScheduler.kt:14)
	at kotlinx.coroutines.scheduling.CoroutineScheduler$Worker.runWorker(CoroutineScheduler.kt:28)
	at kotlinx.coroutines.scheduling.CoroutineScheduler$Worker.run(CoroutineScheduler.kt:0)



Fetching From YT Failed:io.ktor.client.features.ClientRequestException: Client request(https://music.youtube.com/youtubei/v1/search?alt=json&key=AIzaSyC9XL3ZjWddXya6X74dJoCTL-WEYFDNX30) invalid: 404 . Text: "{
  "error": {
    "code": 404,
    "message": "Requested entity was not found.",
    "errors": [
      {
        "message": "Requested entity was not found.",
        "domain": "global",
        "reason": "notFound"
      }
    ],
    "status": "NOT_FOUND"
  }
}
"
	at io.ktor.client.features.DefaultResponseValidationKt$addDefaultResponseValidation$1$1.invokeSuspend(DefaultResponseValidation.kt:199)
	at io.ktor.client.features.DefaultResponseValidationKt$addDefaultResponseValidation$1$1.invoke(Unknown Source:8)
	at io.ktor.client.features.DefaultResponseValidationKt$addDefaultResponseValidation$1$1.invoke(Unknown Source:4)
	at io.ktor.client.features.HttpCallValidator.validateResponse(HttpCallValidator.kt:86)
	at io.ktor.client.features.HttpCallValidator.access$validateResponse(HttpCallValidator.kt:0)
	at io.ktor.client.features.HttpCallValidator$Companion$install$3.invokeSuspend(HttpCallValidator.kt:42)
	at io.ktor.client.features.HttpCallValidator$Companion$install$3.invoke(Unknown Source:11)
	at io.ktor.client.features.HttpCallValidator$Companion$install$3.invoke(Unknown Source:8)
	at io.ktor.client.features.HttpSend$Feature$install$1.invokeSuspend(HttpSend.kt:178)
	at h7.a.resumeWith(ContinuationImpl.kt:10)
	at io.ktor.util.pipeline.SuspendFunctionGun.resumeRootWith(SuspendFunctionGun.kt:55)
	at io.ktor.util.pipeline.SuspendFunctionGun.loop(SuspendFunctionGun.kt:17)
	at io.ktor.util.pipeline.SuspendFunctionGun.access$loop(SuspendFunctionGun.kt:0)
	at io.ktor.util.pipeline.SuspendFunctionGun$continuation$1.resumeWith(SuspendFunctionGun.kt:24)
	at h7.a.resumeWith(ContinuationImpl.kt:33)
	at io.ktor.util.pipeline.SuspendFunctionGun.resumeRootWith(SuspendFunctionGun.kt:55)
	at io.ktor.util.pipeline.SuspendFunctionGun.loop(SuspendFunctionGun.kt:17)
	at io.ktor.util.pipeline.SuspendFunctionGun.access$loop(SuspendFunctionGun.kt:0)
	at io.ktor.util.pipeline.SuspendFunctionGun$continuation$1.resumeWith(SuspendFunctionGun.kt:24)
	at h7.a.resumeWith(ContinuationImpl.kt:33)
	at kotlinx.coroutines.DispatchedTask.run(DispatchedTask.kt:100)
	at kotlinx.coroutines.internal.LimitedDispatcher.run(LimitedDispatcher.kt:12)
	at kotlinx.coroutines.scheduling.TaskImpl.run(Tasks.kt:2)
	at kotlinx.coroutines.scheduling.CoroutineScheduler.runSafely(CoroutineScheduler.kt:0)
	at kotlinx.coroutines.scheduling.CoroutineScheduler$Worker.executeTask(CoroutineScheduler.kt:14)
	at kotlinx.coroutines.scheduling.CoroutineScheduler$Worker.runWorker(CoroutineScheduler.kt:28)
	at kotlinx.coroutines.scheduling.CoroutineScheduler$Worker.run(CoroutineScheduler.kt:0)


)
	at com.shabinder.common.providers.FetchPlatformQueryResult.findBestDownloadLink(FetchPlatformQueryResult.kt:1873)
	at com.shabinder.common.providers.FetchPlatformQueryResult$findBestDownloadLink$1.invokeSuspend(Unknown Source:12)
	at h7.a.resumeWith(ContinuationImpl.kt:10)
	at io.ktor.util.pipeline.SuspendFunctionGun.resumeRootWith(SuspendFunctionGun.kt:74)
	at io.ktor.util.pipeline.SuspendFunctionGun.access$resumeRootWith(SuspendFunctionGun.kt:0)
	at io.ktor.util.pipeline.SuspendFunctionGun$continuation$1.resumeWith(SuspendFunctionGun.kt:17)
	at h7.a.resumeWith(ContinuationImpl.kt:33)
	at io.ktor.util.pipeline.SuspendFunctionGun.resumeRootWith(SuspendFunctionGun.kt:74)
	at io.ktor.util.pipeline.SuspendFunctionGun.access$resumeRootWith(SuspendFunctionGun.kt:0)
	at io.ktor.util.pipeline.SuspendFunctionGun$continuation$1.resumeWith(SuspendFunctionGun.kt:17)
	at h7.a.resumeWith(ContinuationImpl.kt:33)
	at io.ktor.util.pipeline.SuspendFunctionGun.resumeRootWith(SuspendFunctionGun.kt:74)
	at io.ktor.util.pipeline.SuspendFunctionGun.access$resumeRootWith(SuspendFunctionGun.kt:0)
	at io.ktor.util.pipeline.SuspendFunctionGun$continuation$1.resumeWith(SuspendFunctionGun.kt:17)
	at h7.a.resumeWith(ContinuationImpl.kt:33)
	at io.ktor.util.pipeline.SuspendFunctionGun.resumeRootWith(SuspendFunctionGun.kt:74)
	at io.ktor.util.pipeline.SuspendFunctionGun.access$resumeRootWith(SuspendFunctionGun.kt:0)
	at io.ktor.util.pipeline.SuspendFunctionGun$continuation$1.resumeWith(SuspendFunctionGun.kt:17)
	at h7.a.resumeWith(ContinuationImpl.kt:33)
	at io.ktor.util.pipeline.SuspendFunctionGun.resumeRootWith(SuspendFunctionGun.kt:55)
	at io.ktor.util.pipeline.SuspendFunctionGun.loop(SuspendFunctionGun.kt:17)
	at io.ktor.util.pipeline.SuspendFunctionGun.access$loop(SuspendFunctionGun.kt:0)
	at io.ktor.util.pipeline.SuspendFunctionGun$continuation$1.resumeWith(SuspendFunctionGun.kt:24)
	at h7.a.resumeWith(ContinuationImpl.kt:33)
	at io.ktor.util.pipeline.SuspendFunctionGun.resumeRootWith(SuspendFunctionGun.kt:55)
	at io.ktor.util.pipeline.SuspendFunctionGun.loop(SuspendFunctionGun.kt:17)
	at io.ktor.util.pipeline.SuspendFunctionGun.access$loop(SuspendFunctionGun.kt:0)
	at io.ktor.util.pipeline.SuspendFunctionGun$continuation$1.resumeWith(SuspendFunctionGun.kt:24)
	at h7.a.resumeWith(ContinuationImpl.kt:33)
	at kotlinx.coroutines.DispatchedTask.run(DispatchedTask.kt:100)
	at kotlinx.coroutines.internal.LimitedDispatcher.run(LimitedDispatcher.kt:12)
	at kotlinx.coroutines.scheduling.TaskImpl.run(Tasks.kt:2)
	at kotlinx.coroutines.scheduling.CoroutineScheduler.runSafely(CoroutineScheduler.kt:0)
	at kotlinx.coroutines.scheduling.CoroutineScheduler$Worker.executeTask(CoroutineScheduler.kt:14)
	at kotlinx.coroutines.scheduling.CoroutineScheduler$Worker.runWorker(CoroutineScheduler.kt:28)
	at kotlinx.coroutines.scheduling.CoroutineScheduler$Worker.run(CoroutineScheduler.kt:0)
