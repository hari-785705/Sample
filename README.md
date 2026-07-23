# Computer Vision & NLP Lab

R23 Regulations · CSE-AI · III B.Tech I Semester
Course: 23LC4302 — Computer Vision and NLP Lab

A small React app that presents all 12 lab experiments (aim, theory,
program, explanation, and result) with a sidebar to switch between them.

## Structure

```
src/
├── components/
│   ├── Program1.jsx   Load/display image, resize, crop, rotate
│   ├── Program2.jsx   Edge detection (Sobel, Canny) & thresholding
│   ├── Program3.jsx   Gaussian / Median / Bilateral filtering
│   ├── Program4.jsx   Contour detection & bounding boxes
│   ├── Program5.jsx   Face detection (Haar Cascade)
│   ├── Program6.jsx   Color-based tracking (HSV + CamShift)
│   ├── Program7.jsx   Text preprocessing (tokenize/stem/lemmatize)
│   ├── Program8.jsx   POS tagging & NER with spaCy
│   ├── Program9.jsx   Sentiment analysis (TF-IDF + Naive Bayes)
│   ├── Program10.jsx  Topic modeling (LDA)
│   ├── Program11.jsx  OCR (Tesseract) + text summarization
│   └── Program12.jsx  Mini project: CV + NLP (OCR + translate)
├── App.js
├── App.css
└── index.js
package.json
.gitignore
README.md
```

## Run locally

```
npm install
npm start
```

Then open http://localhost:3000
