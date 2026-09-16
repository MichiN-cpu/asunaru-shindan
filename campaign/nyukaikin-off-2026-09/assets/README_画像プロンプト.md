# キャンペーンLP用 画像プロンプト（ChatGPT/DALL-E用）

LPコード側は以下の2枚が来る前提で組んであります。ChatGPTで生成した画像は、このファイル名で本フォルダ（`assets/`）に保存してください。

- `hero-couple.jpg`（横長・ページ最上部の背景に使用。1792×1024推奨）
- `moment-photo.jpg`（横長・本文内に挿入。1792×1024推奨）

保存すればLPは自動でその画像を表示します（コード修正不要）。

---

## 1. hero-couple.jpg（ページ最上部・世界観を見せる1枚）

```
Photorealistic, cinematic quality, natural bright lighting, East Asian appearance,
a beautiful Japanese couple in their early 30s, elegant refined features, model-like appearance, clear skin,
genuinely laughing and looking at each other with joy,
the woman in an elegant white wedding dress holding a bouquet of white and blush pink flowers,
the man in a light beige suit,
soft flower petals gently floating in the air around them,
bright airy indoor venue with large windows and natural light streaming in,
professional wedding lifestyle photography style, shallow depth of field,
clean bright modern atmosphere, heartfelt genuine emotion,
no text, no logo, no watermark, horizontal 16:9 composition
```

## 2. moment-photo.jpg（本文中・「喜びを渡すから、また喜びが返ってくる」の一枚）

```
Photorealistic, cinematic quality, natural bright lighting, East Asian appearance,
a beautiful Japanese couple in their early 30s, elegant refined features, model-like appearance, clear skin,
sitting close together at an outdoor cafe table in soft afternoon light,
the man gently handing the woman a small bouquet of flowers,
both smiling brightly with genuine happiness, natural candid moment,
professional lifestyle photography style, shallow depth of field,
clean bright modern atmosphere,
no text, no logo, no watermark, horizontal 16:9 composition
```

---

## 使い方メモ

- ベースの指定（フォトリアル・イラスト禁止・美人度高め・"warm tones"という言葉は使わない＝黄ばみ防止）は、ブログ画像と同じルール（`feedback_image_style.md`）に合わせています
- 生成後、雰囲気が違う・顔がイマイチ等あれば、その部分だけ言い換えて再生成してOKです（例：「もっと自然な笑顔に」「花をもっと少なく」など）
- 1枚目（hero）は本文の上に白文字で見出しが重なるので、**画面の下1/3が暗すぎず明るすぎない**構図が理想です（人物を画面中央〜やや上に、下部は空間が空いている構図だと収まりが良いです）
- 気に入った案が複数あれば両方送ってください。差し替えはこちらで数分で対応できます
