# kstory-assets

kstory 기사 제출(MCP)용 이미지 저장소. 영상 본편에서 뽑은 프레임을 여기에 올리고, 그 URL 을 kstory MCP 도구(`check_images`, `submit_article`)에 전달한다.

## 폴더 규칙

```
images/<업로드 날짜 YYYY-MM-DD>/<유튜브 영상 ID>/<용도>-<초>.jpg
예) images/2026-09-28/16sJlEIQY-U/cover-083.jpg
```
- `<용도>`: `cover`(커버 후보) / `body`(본문 참고 이미지), `<초>`: 영상에서 뽑은 시각(초).
- 한글·공백 파일명 금지, 덮어쓰지 말고 새 이름으로 올린다.

## MCP 에 줄 URL

`https://raw.githubusercontent.com/aiinplanet/kstory-assets/main/<경로>` (파일 보기 주소 `.../blob/main/<경로>` 도 받는다)

## 올릴 수 있는 이미지

- 공식 채널 영상 **본편에서 직접 뽑은 프레임**만. 유튜브 채널 대표 썸네일·언론사 사진·팬캠 금지.
- jpeg·png·webp, 가로 640px 이상·가로형(16:9 권장), 10MB 이하, 원본 해상도 그대로.
- 자세한 기준은 kstory MCP `get_image_guide` 참고.
