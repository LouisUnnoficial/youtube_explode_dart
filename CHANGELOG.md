## 0.0.1

- Initial version, created by Stagehand

## 0.0.2

- Implement channel api

## 0.0.3

- Remove `dart:io` dependency.

## 0.0.4

- Fix #3 : Head request to ge the content length
- Fix error when getting videos without any keyword.

## 0.0.5

- Implement Search Api (`SearchExtension`)

## 0.0.6

- Implement Caption Api ('CaptionExtension`)
- Add Custom Exceptions

## 0.0.7

- Implement Video Purchase error
- Implement Equatable for models

## 0.0.8

- Downgrade xml to `^3.5.0`

## 0.0.9

- Bug Fix(PR [11][11]): Use url when retrieving the video's content length.

[11]: https://github.com/Hexer10/youtube_explode_dart/pull/11

## 0.0.10

- Bug fix: Don't throw when captions are not present.
- New extension: CaptionListExtension adding `getByTime` function.

## 0.0.11

- New extension: DownloadExtension adding `downloadStream` function.

## 0.0.12

- Bug fix(#15): Fix invalid upload date.

## 0.0.13

- Bug fix(#15): Fix valid channel expression

## 0.0.14

- getChannelWatchPage and getVideoWatchPage methods are now public
- New method: getChannelIdFromVideo

## 0.0.15

- Workaround (#15): Now when a video is not available a `VideoUnavailable` exception is thrown
- Removed disable_polymer parameter when requests ( https://github.com/Tyrrrz/YoutubeExplode/issues/341 )
- Removed `dart:io` dependency

## 0.0.16

- When a video is not available(403) a `VideoStreamUnavailableException` 