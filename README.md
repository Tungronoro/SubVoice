# SubVoice

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=250&section=header&text=%F0%9F%8E%99%EF%B8%8F%20SubVoice&fontSize=75&fontColor=ffffff&animation=fadeIn&fontAlignY=37&desc=Reads%20Subtitles%20Aloud%20with%20Natural%20AI%20Voices%20%E2%80%A2%20Perfect%20Sync&descAlignY=61&descSize=18" alt="SubVoice Banner"/>

<a href="https://github.com/Tungronoro/SubVoice">
  <img src="https://readme-typing-svg.demolab.com?font=Be+Vietnam+Pro&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=940&lines=%F0%9F%8E%AC+Video+%2B+Audio+Player+with+Dual+Subtitles;+%F0%9F%97%A3%EF%B8%8F+Natural+AI+Voices+in+Perfect+Sync+with+Video;+%E2%96%B6+Xem+phim+%E2%80%A2+Nghe+nh%E1%BA%A1c+%E2%80%A2+H%E1%BB%8Dc+ti%E1%BA%BFng+Anh+si%C3%AAu+hay" alt="Typing SVG"/>
</a>

<br/>

<p>
  <a href="https://github.com/Tungronoro/SubVoice/releases">
    <img src="https://img.shields.io/github/v/release/Tungronoro/SubVoice?style=for-the-badge&logo=windows&logoColor=white&label=Download&color=0078D4" alt="Latest Release"/>
  </a>
  <a href="https://www.youtube.com/playlist?list=PLYnMAMqLtnWE">
    <img src="https://img.shields.io/badge/YouTube-Demo_Full-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube Demo"/>
  </a>
  <img src="https://img.shields.io/badge/Windows-10_%2F_11-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows"/>
  <img src="https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
</p>

<p>
  <img src="https://img.shields.io/github/stars/Tungronoro/SubVoice?style=social" alt="Stars"/>
  <img src="https://img.shields.io/github/forks/Tungronoro/SubVoice?style=social" alt="Forks"/>
  <img src="https://img.shields.io/github/watchers/Tungronoro/SubVoice?style=social" alt="Watchers"/>
</p>

<p>
  <a href="https://github.com/Tungronoro/SubVoice/releases"><b>⬇️ Tải SubVoice_Setup.exe</b></a>
  &nbsp;•&nbsp;
  <a href="https://www.youtube.com/playlist?list=PLYnMAMqLtnWE"><b>📺 Video Demo</b></a>
  &nbsp;•&nbsp;
  <a href="#features"><b>✨ Tính năng</b></a>
</p>

> 🎧 **SubVoice — Trình phát video & audio đọc phụ đề bằng giọng AI tự nhiên, đồng bộ hoàn hảo với video.**
> *A Windows app that reads subtitles aloud using natural AI voices in perfect sync with video playback.*

</div>


## Tiếng Việt

### Demo video

<video src="https://github.com/Tungronoro/SubVoice/releases/download/V3.0.8/SubVoice_Demo_V3.0.8.mp4" controls width="100%"></video>

[Tải video demo](https://github.com/Tungronoro/SubVoice/releases/download/V3.0.8/SubVoice_Demo_V3.0.8.mp4)

### Demo video

<video src="https://github.com/Tungronoro/SubVoice/releases/download/V3.0.8/SubVoice_Demo_V3.0.8.mp4" controls width="100%"></video>

[Tải video demo](https://github.com/Tungronoro/SubVoice/releases/download/V3.0.8/SubVoice_Demo_V3.0.8.mp4)

### Demo video

<video src="https://github.com/Tungronoro/SubVoice/releases/download/V3.0.8/SubVoice_Demo_V3.0.8.mp4" controls width="100%"></video>

[Tải video demo](https://github.com/Tungronoro/SubVoice/releases/download/V3.0.8/SubVoice_Demo_V3.0.8.mp4)

### Giới thiệu

SubVoice là trình phát video và audio hỗ trợ giọng đọc AI. Phần mềm cho phép người dùng xem phim, nghe nhạc, sử dụng phụ đề và tạo lời đọc thuyết minh theo nội dung phụ đề.

### Trạng thái / bước tiếp theo

- 2026-10-10: tab YouTube bỏ nút chọn thư mục tạm (chọn ở **Cài đặt → Quản lý dữ liệu**), thư mục tải về đặt tên `<tiêu đề> [<id>]` — regression YouTube PASS.
- Chưa commit/chưa build: `data_storage.py` đổi tên thư mục sang bản không dấu (`App Data`, `Voice Clone`, ...) kèm tự hợp nhất tên cũ có dấu; bản đang cài là 3.0.5 nên **giữ cả tên có dấu** cho tới khi cài bản build mới.

### Dang am thanh - chon dinh dang output (2026-10-10)
- Bat "Chỉ lấy âm thanh - không lấy video" rồi chon "Định dạng âm thanh"
  (M4A / MP3 320 kbps / FLAC / WAV / OGG / Opus) để tải am thanh chất lượng
  cao nhất của YouTube rồi chuyển sang định dạng người dùng chọn. FFmpeg
  (đã đồng bộ trong bản cài) đảm bảo chuyển mã; khi không có FFmpeg, file giữ
  nguyên định dạng gốc và hiển thị cảnh báo.


### Tính năng

- Phát video và các file audio phổ biến.
- Hỗ trợ phụ đề 1 và phụ đề 2.
- Chỉnh vị trí, kích thước, màu sắc và đồng bộ thời gian phụ đề.
- Hỗ trợ nhiều engine và giọng đọc AI hiện có trong phần mềm.
- Điều chỉnh âm lượng phim gốc, âm lượng giọng đọc và tốc độ giọng đọc.
- Phát, tạm dừng, tua nhanh, tua lại, xem lại từ đầu và chuyển tập.
- Chế độ toàn màn hình và nhiều giao diện màu sắc.
- Ghi nhớ vị trí xem và lịch sử xem phim.
- Lịch sử tạo giọng: xem phim nào đã tạo giọng nào, rồi phát lại đúng phim kèm đúng giọng thuyết minh trong một cú bấm.
- Hỗ trợ phím tắt để điều khiển nhanh.
- Chụp ảnh khung hình video.
- Ghép cache giọng thuyết minh thành một file MP3 hoàn chỉnh theo timeline phụ đề; file có thể dài hơn video nếu phụ đề còn câu sau phần cuối video.
- Quản lý thư mục gốc dữ liệu SubVoice, gồm MP3 thuyết minh, cache TTS, YouTube, dữ liệu clone, phụ đề trích xuất, tệp tạm, cấu hình và log trong tab **Cài đặt → Quản lý dữ liệu**.

### Hướng dẫn cài đặt

1. Tải file cài đặt SubVoice do tác giả cung cấp, ví dụ `SubVoice_Setup.exe`.
2. Nhấp đúp vào file Setup.
3. Làm theo hướng dẫn trên màn hình và chọn **Install**.
4. Sau khi cài đặt hoàn tất, mở SubVoice từ biểu tượng trên Desktop hoặc trong Start Menu.

Không cần tải hoặc cài mã nguồn để sử dụng phần mềm. Không di chuyển hoặc xóa các file do trình cài đặt tạo ra trong thư mục cài đặt.

### Hướng dẫn sử dụng

Mở SubVoice, sau đó chọn file video hoặc audio để phát. Người dùng cũng có thể mở file bằng SubVoice từ Windows hoặc kéo một file vào cửa sổ phần mềm.

Để sử dụng phụ đề, chọn phụ đề 1 hoặc phụ đề 2 trong phần **Cài đặt**. Tại đây, người dùng có thể chỉnh vị trí, kích thước, màu sắc và thời gian đồng bộ của từng phụ đề.

Để bật giọng đọc AI, mở **Cài đặt → Thư viện giọng đọc**, chọn engine và giọng đọc, sau đó tạo giọng cho Phụ đề 1 đến khi hoàn tất 100%. Để xuất thành một file MP3 hoàn chỉnh, mở **Cài đặt → Xuất giọng thuyết minh**, điều chỉnh tốc độ giọng đọc rồi chọn **Ghép và xuất MP3**. File được ghép theo toàn bộ timeline của phụ đề hiện tại. Khi đang xem, có thể dùng các nút điều khiển trên trình phát hoặc phím tắt được hiển thị trong phần **Cài đặt → Phím tắt**.

Để quản lý nơi lưu dữ liệu, mở **Cài đặt → Quản lý dữ liệu**. SubVoice gom cache TTS, MP3 thuyết minh, YouTube, dữ liệu clone, phụ đề trích xuất, tệp tạm, cấu hình và log vào một thư mục gốc chia thành các thư mục con. Mục **Dữ liệu clone giọng** chỉ hiện đường dẫn và nút **Mở thư mục**; người dùng tự xem hoặc xóa tệp. Video và phụ đề nguồn không bị di chuyển.

Để mở file khác, dùng chức năng mở file hoặc kéo một file video/audio mới vào phần mềm. Khi mở file mới, nội dung đang phát sẽ được thay thế bằng file mới.

Để xem lại phim đã tạo giọng, mở **Cài đặt → Lịch sử tạo giọng**. Mỗi bản ghi cho biết phim nào đã tạo bằng engine và giọng nào. Bấm **Phát lại** để mở đúng phim kèm đúng giọng thuyết minh đó. Tab hiển thị trạng thái của từng bản ghi để biết giọng có còn dùng được hay không: ✅ Sẵn sàng, ♻️ Giọng đã bị xóa, ⚠ Phụ đề đã đổi, 📄 Thiếu phụ đề, ❌ Mất file phim.

> Lưu ý V3.0.7: **Không có thay đổi so với V3.0.6**. Phiên bản này **chỉ để test chức năng cập nhật phần mềm** (auto-updater). Toàn bộ tính năng, mã nguồn, cài đặt, dữ liệu giữ nguyên 100%. Xem `Release_Notes_V3.0.7_GitHub.md` để biết chi tiết.
>
> Lưu ý V3.0.6: Bản này tập trung **ổn định**, **tối ưu dung lượng**, **quản lý bộ nhớ/model tốt hơn**. Bổ sung **Quản lý model TTS** (`Cài đặt → Thư viện giọng đọc → Quản lý model`): xem manifest, tải/xóa model theo nhu cầu (VieNeu Turbo/Nano, V-TTS, Piper), resume tải, verify SHA-256, mở thư mục model, dark title bar đồng bộ. Model tách riêng `%LOCALAPPDATA%\SubVoice\Models`, không gộp với dữ liệu người dùng. Xem `Release_Notes_V3.0.6_GitHub.md` để biết chi tiết.
>
> Lưu ý V3.0.5: Bản này bổ sung tab **Cài đặt → Lịch sử tạo giọng**, cho phép xem phim nào đã tạo giọng nào và phát lại đúng phim kèm đúng giọng thuyết minh. Đồng thời sửa lỗi xuất MP3 bị chặn với engine clone giọng, sửa lỗi khôi phục khi đổi thư mục gốc dữ liệu, và sửa lỗi nút "Thử lại" chỉ tạo lại một phần giọng đọc. Xem `Release_Notes_V3.0.5_GitHub.md` để biết chi tiết.
>
> Lưu ý V3.0.4: Engine giọng đọc VieNeu-TTS (20 giọng preset, cùng tính năng clone giọng từ file tiếng tham chiếu) đã được **đóng gói nguyên bộ trong bộ cài**, vì vậy hoạt động ngay sau khi cài đặt trên máy tính mới chưa từng cài đặt, **không cần kết nối internet**. Edge TTS là dịch vụ trực tuyến nên vẫn cần mạng. Xem `Release_Notes_V3.0.4_GitHub.md` để biết chi tiết.

### Sao lưu dữ liệu model

Mã nguồn SubVoice được lưu trong Git và push lên GitHub bình thường. Riêng một số
thư mục model **không** đưa vào Git vì có file vượt giới hạn 100 MB của GitHub
(lớn nhất là `vieneu_bundle_nano/vector_estimator.onnx` khoảng 148 MB), nếu đưa vào
sẽ khiến toàn bộ lần push bị từ chối.

Các thư mục cần sao lưu riêng:

| Thư mục | Dung lượng | Nội dung |
|---|---|---|
| `vieneu_bundle/` | ~312 MB | Model VieNeu v3 Turbo (đã nằm trong Git) |
| `vieneu_bundle_nano/` | ~400 MB | Model VieNeu v3 Nano |
| `voice_samples/vieneu_nano/` | ~16 MB | Mẫu giọng Nano để nghe thử |
| `vtts_zeroshot_refs/` | ~3 MB | Tệp giọng tham chiếu cho clone giọng |

Cách sao lưu an toàn (không qua Git):

```powershell
# Gộp các thư mục model vào một file ZIP để copy sang ổ khác
Compress-Archive -Path vieneu_bundle, vieneu_bundle_nano, voice_samples\vieneu_nano, vtts_zeroshot_refs `
  -DestinationPath D:\SubVoice_model_backup.zip -CompressionLevel Optimal
```

Hoặc chỉ cần copy nguyên thư mục project sang ổ cứng/ở mạng khác. Nếu máy có mạng
và chạy lại công cụ chuẩn bị bundle, có thể tạo lại model bằng:

```powershell
python tools\prepare_vieneu_bundle.py --with-nano
```

Ngoài ra, dữ liệu người dùng (cache TTS, MP3 thuyết minh, video tải về, lịch sử xem)
**không nằm trong thư mục project** mà nằm ở thư mục gốc dữ liệu riêng. Xem đường dẫn
hiện tại trong **Cài đặt → Quản lý dữ liệu**, hoặc trong tệp chỉ dẫn
`%APPDATA%\SubVoice\subvoice_data_location.json`.

---

## English

### Demo video

<video src="https://github.com/Tungronoro/SubVoice/releases/download/V3.0.8/SubVoice_Demo_V3.0.8.mp4" controls width="100%"></video>

[Download demo video](https://github.com/Tungronoro/SubVoice/releases/download/V3.0.8/SubVoice_Demo_V3.0.8.mp4)

### Demo video

<video src="https://github.com/Tungronoro/SubVoice/releases/download/V3.0.8/SubVoice_Demo_V3.0.8.mp4" controls width="100%"></video>

[Download demo video](https://github.com/Tungronoro/SubVoice/releases/download/V3.0.8/SubVoice_Demo_V3.0.8.mp4)

### Demo video

<video src="https://github.com/Tungronoro/SubVoice/releases/download/V3.0.8/SubVoice_Demo_V3.0.8.mp4" controls width="100%"></video>

[Download demo video](https://github.com/Tungronoro/SubVoice/releases/download/V3.0.8/SubVoice_Demo_V3.0.8.mp4)

### Introduction

SubVoice is a video and audio player with AI voice narration support. It allows users to watch videos, listen to music, use subtitles, and generate narrated audio from subtitle content.

### Features

- Play video and common audio files.
- Support Subtitle 1 and Subtitle 2.
- Adjust subtitle position, size, color, and timing.
- Support the AI TTS engines and voices included in the application.
- Adjust original audio volume, narration volume, and narration speed.
- Play, pause, seek forward, seek backward, restart, and switch episodes.
- Full-screen mode and multiple color themes.
- Remember playback position and viewing history.
- Voice history: see which movie had narration generated with which voice, then replay that exact combination in one click.
- Keyboard shortcuts for quick control.
- Capture video frames as images.
- Merge the narration cache into a complete MP3 file using the subtitle timeline; the MP3 may be longer than the video when subtitles continue beyond the video end.
- Manage one centralized SubVoice data root containing dubbed MP3 files, TTS cache, YouTube downloads, clone data, extracted subtitles, temporary files, settings, and logs from **Settings → Data Management**.

### Installation Guide

1. Download the SubVoice installer provided by the author, for example `SubVoice_Setup.exe`.
2. Double-click the Setup file.
3. Follow the on-screen instructions and select **Install**.
4. After installation is complete, launch SubVoice from the Desktop shortcut or the Start Menu.

You do not need to download or install the source code to use the application. Do not move or delete files created by the installer inside the installation folder.

### User Guide

Open SubVoice and select a video or audio file to play. You can also open a file with SubVoice from Windows or drag one file into the application window.

To use subtitles, select Subtitle 1 or Subtitle 2 in **Settings**. You can adjust the position, size, color, and synchronization timing of each subtitle there.

To enable AI narration, open **Settings → Voice Library**, choose an engine and voice, and generate narration for Subtitle 1 until it reaches 100%. To export a complete MP3 file, open **Settings → Dubbed Voice Export**, adjust the narration speed, and select **Merge and export MP3**. The file is merged across the full timeline of the current subtitles. During playback, you can use the player controls or the keyboard shortcuts listed in **Settings → Shortcuts**.

> V3.0.5 note: This release adds the **Settings → Voice History** tab, which shows which movie had narration generated with which voice and replays that exact combination in one click. It also fixes the MP3 export being blocked for voice-cloning engines, fixes incomplete rollback when changing the data root folder, and fixes the Retry button regenerating only part of the narration. See `Release_Notes_V3.0.5_GitHub.md` for details.
>
> V3.0.4 note: The VieNeu-TTS voice engine (20 preset voices, plus voice cloning from a reference audio file) is **fully bundled inside the installer**, so it works immediately after install on a fresh Windows machine with **no internet required**. Edge TTS is an online service and still requires a network connection. See `Release_Notes_V3.0.4_GitHub.md` for details.

To open another file, use the Open File function or drag a new video/audio file into the application. The currently playing media will be replaced by the new file.

