<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<title>한글 타자연습</title>
<style>
    body {
        font-family: "맑은 고딕", sans-serif;
        text-align: center;
        background: #f5f5f5;
        margin: 0;
        padding: 20px;
    }
    h1 {
        color: #333;
    }
    #modeSelect button {
        padding: 10px 20px;
        font-size: 1em;
        margin: 5px;
        border: none;
        background: #2196F3;
        color: white;
        border-radius: 5px;
        cursor: pointer;
    }
    #modeSelect button:hover {
        background: #1976D2;
    }
    #quote {
        font-size: 1.4em;
        background: #fff;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 0 10px rgba(0,0,0,0.1);
        margin: 20px auto;
        display: inline-block;
        max-width: 600px;
    }
    input {
        width: 60%;
        padding: 10px;
        font-size: 1.2em;
        border-radius: 5px;
        border: 1px solid #ccc;
    }
    #result {
        margin-top: 20px;
        font-size: 1.1em;
    }
    #retryBtn {
        padding: 10px 20px;
        font-size: 1em;
        margin-top: 10px;
        border: none;
        background: #4CAF50;
        color: white;
        border-radius: 5px;
        cursor: pointer;
    }
    #retryBtn:hover {
        background: #45a049;
    }
</style>
</head>
<body>

<h1>한글 타자연습</h1>

<div id="modeSelect">
    <button onclick="setMode('word')">난말 연습</button>
    <button onclick="setMode('sentence')">단문 연습</button>
</div>

<div id="quote"></div>
<br>
<input type="text" id="input" placeholder="여기에 입력하세요" autofocus>
<div id="result"></div>
<button id="retryBtn" onclick="newQuote()">다시 하기</button>

<script>
const wordList = [
    "바다", "하늘", "강아지", "사과", "책상", "우유", "고양이", "바람", "햇빛", "연필",
    "학교", "산책", "비행기", "커피", "친구", "도서관", "꽃", "나무", "피아노", "연습"
];

const sentenceList = [
    "오늘은 날씨가 참 맑습니다.",
    "나는 매일 아침 커피를 마십니다.",
    "강아지가 마당에서 뛰어놀고 있습니다.",
    "피아노 연습을 하면 실력이 향상됩니다.",
    "책을 읽는 것은 마음을 풍요롭게 합니다."
];

let mode = "word"; // 기본 모드
let startTime;
let currentQuote = "";

function setMode(selectedMode) {
    mode = selectedMode;
    newQuote();
}

function newQuote() {
    if (mode === "word") {
        currentQuote = wordList[Math.floor(Math.random() * wordList.length)];
    } else {
        currentQuote = sentenceList[Math.floor(Math.random() * sentenceList.length)];
    }
    document.getElementById("quote").textContent = currentQuote;
    document.getElementById("input").value = "";
    document.getElementById("result").textContent = "";
    startTime = new Date().getTime();
}

document.getElementById("input").addEventListener("input", function() {
    const typed = this.value;
    if (typed === currentQuote) {
        const endTime = new Date().getTime();
        const timeTaken = (endTime - startTime) / 1000;
        const speed = (currentQuote.length / timeTaken) * 60;
        document.getElementById("result").textContent = 
            `완료! ⏱ 시간: ${timeTaken.toFixed(2)}초, ⌨ 속도: ${speed.toFixed(2)} 타/분`;
    }
});

newQuote();
</script>

</body>
</html>
