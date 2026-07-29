# Key Detector

DAW (FL Studio, Ableton vb.) için geliştirilmiş web tabanlı müzik analiz aracı.

## Özellikler

- **MIDI & Audio analizi** — `.mid`, `.midi`, `.mp3`, `.wav` dosyalarını destekler
- **Key detection** — Krumhansl-Schmuckler algoritması ile otomatik ton tespiti
- **Dikey piano roll** — DAW stilinde, scale notaları renk kodlu gösterim
- **Bassline önerileri** — Keye göre öncelikli nota önerileri
- **Chord progressions** — 6 farklı tür (Pop, R&B, Hip-hop, Jazz vb.)
- **Piano roll modal** — Her progression için FL Studio stili nota görünümü
- **Manuel override** — Yanlış tespiti düzeltme imkânı

## Kullanım

`index.html` 

## Teknolojiler

- Vanilla JS / HTML5 Canvas
- [@tonejs/midi](https://github.com/Tonejs/Midi) — MIDI parsing
- Krumhansl-Schmuckler key detection
- Goertzel algoritması — audio chromagram analizi
- Web Audio API

## Geliştirme Notları

- Chord progression önerileri: minör ve majör için 6'şar adet

