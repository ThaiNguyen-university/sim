
<html>

<head>
    <title>Biểu mẫu thử nghiệm phân biệt người nói 1</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.1/css/bootstrap.min.css"
        integrity="sha384-VCmXjywReHh4PwowAiWNagnWcLhlEJLA5buUprzK8rxFgeH0kww/aWY76TfkUoSX" crossorigin="anonymous">
</head>

<body>
    <div class="jumbotron jumbotron-fluid">
        <div class="container">

    <h1 class="display-4">Thử nghiệm phân biệt người nói</h1>
    <p class="lead">Xác định xem hai giọng nói có phải là của cùng một người hay không</p>
    <hr class="my-4">
    <p>
        Cảm ơn bạn đã tham gia thử nghiệm này!
    </p>
    <p>
       Trong thí nghiệm này, chúng tôi sử dụng máy tính tổng hợp và chuyển đổi giọng nói của con người. Mỗi câu hỏi có hai tệp âm thanh, sau khi nghe bằng tai nghe, hãy trả lời theo mức độ giống nhau của người nói của hai tệp âm thanh (chỉ xét giọng nói của người nói, không xét nội dung của câu)。
    </p>
    <p>
        Tiêu chuẩn chấm điểm là：
        <ul>
            <li>1. Chắc chắn là giống nhau (Definitely the same)</li>
            <li>2. Có thể giống (Maybe the same)</li>
            <li>3. Có thể khác nhau (Maybe different)</li>
            <li>4. Chắc chắn là khác (Definitely different)</li>
        </ul>
    </p>

        </div>
    </div>

    <div class="container" id="form_container">
        <form id="theForm" action="https://script.google.com/macros/s/AKfycbwqGOGjaJhp78Tpv7UXmxNObVPMjst_fvPo6gHzL2426PtAwl4qLL01mqiswFecqe3z/exec" method="GET" onsubmit="return preventRepeatedSubmission();">
            <div class="form-group">
                <label for="name">Tên：</label>
                <input class="form-control" type="text" inputmode="text" name="name" required>
                <small class="form-text text-muted">Cần thiết*</small>
            </div>
            <div class="form-group">
                <label for="mail">E-mail：</label>
                <input class="form-control" type="text" inputmode="email" placeholder="account@example.com" name="mail">
                <small class="form-text text-muted">Nếu bạn thắng, chúng tôi sẽ thông báo cho bạn qua email</small>
            </div>

<div class="card form-group">
        <div class="card-header">Câu 26</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0011.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(26).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="26" id="q26_1" value="1" required>
                <label class="form-check-label" for="q26_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="26" id="q26_2" value="2" required>
                <label class="form-check-label" for="q26_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="26" id="q26_3" value="3" required>
                <label class="form-check-label" for="q26_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="26" id="q26_4" value="4" required>
                <label class="form-check-label" for="q26_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 42</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-98-0008.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/29.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="42" id="q42_1" value="1" required>
                <label class="form-check-label" for="q42_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="42" id="q42_2" value="2" required>
                <label class="form-check-label" for="q42_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="42" id="q42_3" value="3" required>
                <label class="form-check-label" for="q42_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="42" id="q42_4" value="4" required>
                <label class="form-check-label" for="q42_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 39</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-98-0003.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/24.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="39" id="q39_1" value="1" required>
                <label class="form-check-label" for="q39_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="39" id="q39_2" value="2" required>
                <label class="form-check-label" for="q39_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="39" id="q39_3" value="3" required>
                <label class="form-check-label" for="q39_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="39" id="q39_4" value="4" required>
                <label class="form-check-label" for="q39_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 37</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-98-0001.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/22.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="37" id="q37_1" value="1" required>
                <label class="form-check-label" for="q37_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="37" id="q37_2" value="2" required>
                <label class="form-check-label" for="q37_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="37" id="q37_3" value="3" required>
                <label class="form-check-label" for="q37_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="37" id="q37_4" value="4" required>
                <label class="form-check-label" for="q37_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 34</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-97-0001.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/3.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="34" id="q34_1" value="1" required>
                <label class="form-check-label" for="q34_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="34" id="q34_2" value="2" required>
                <label class="form-check-label" for="q34_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="34" id="q34_3" value="3" required>
                <label class="form-check-label" for="q34_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="34" id="q34_4" value="4" required>
                <label class="form-check-label" for="q34_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 56</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0011.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/54.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="56" id="q56_1" value="1" required>
                <label class="form-check-label" for="q56_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="56" id="q56_2" value="2" required>
                <label class="form-check-label" for="q56_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="56" id="q56_3" value="3" required>
                <label class="form-check-label" for="q56_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="56" id="q56_4" value="4" required>
                <label class="form-check-label" for="q56_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 18</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-104-0021.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(18).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="18" id="q18_1" value="1" required>
                <label class="form-check-label" for="q18_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="18" id="q18_2" value="2" required>
                <label class="form-check-label" for="q18_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="18" id="q18_3" value="3" required>
                <label class="form-check-label" for="q18_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="18" id="q18_4" value="4" required>
                <label class="form-check-label" for="q18_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 6</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-97-0014.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(6).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="6" id="q6_1" value="1" required>
                <label class="form-check-label" for="q6_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="6" id="q6_2" value="2" required>
                <label class="form-check-label" for="q6_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="6" id="q6_3" value="3" required>
                <label class="form-check-label" for="q6_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="6" id="q6_4" value="4" required>
                <label class="form-check-label" for="q6_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 30</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0026.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(30).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="30" id="q30_1" value="1" required>
                <label class="form-check-label" for="q30_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="30" id="q30_2" value="2" required>
                <label class="form-check-label" for="q30_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="30" id="q30_3" value="3" required>
                <label class="form-check-label" for="q30_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="30" id="q30_4" value="4" required>
                <label class="form-check-label" for="q30_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 23</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0006.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(23).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="23" id="q23_1" value="1" required>
                <label class="form-check-label" for="q23_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="23" id="q23_2" value="2" required>
                <label class="form-check-label" for="q23_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="23" id="q23_3" value="3" required>
                <label class="form-check-label" for="q23_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="23" id="q23_4" value="4" required>
                <label class="form-check-label" for="q23_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 59</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0018.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/59.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="59" id="q59_1" value="1" required>
                <label class="form-check-label" for="q59_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="59" id="q59_2" value="2" required>
                <label class="form-check-label" for="q59_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="59" id="q59_3" value="3" required>
                <label class="form-check-label" for="q59_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="59" id="q59_4" value="4" required>
                <label class="form-check-label" for="q59_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 2</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-96-0007.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(2).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="2" id="q2_1" value="1" required>
                <label class="form-check-label" for="q2_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="2" id="q2_2" value="2" required>
                <label class="form-check-label" for="q2_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="2" id="q2_3" value="3" required>
                <label class="form-check-label" for="q2_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="2" id="q2_4" value="4" required>
                <label class="form-check-label" for="q2_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 50</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-104-0025.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/44.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="50" id="q50_1" value="1" required>
                <label class="form-check-label" for="q50_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="50" id="q50_2" value="2" required>
                <label class="form-check-label" for="q50_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="50" id="q50_3" value="3" required>
                <label class="form-check-label" for="q50_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="50" id="q50_4" value="4" required>
                <label class="form-check-label" for="q50_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 19</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-104-0022.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(19).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="19" id="q19_1" value="1" required>
                <label class="form-check-label" for="q19_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="19" id="q19_2" value="2" required>
                <label class="form-check-label" for="q19_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="19" id="q19_3" value="3" required>
                <label class="form-check-label" for="q19_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="19" id="q19_4" value="4" required>
                <label class="form-check-label" for="q19_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 33</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-96-0008.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/2.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="33" id="q33_1" value="1" required>
                <label class="form-check-label" for="q33_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="33" id="q33_2" value="2" required>
                <label class="form-check-label" for="q33_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="33" id="q33_3" value="3" required>
                <label class="form-check-label" for="q33_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="33" id="q33_4" value="4" required>
                <label class="form-check-label" for="q33_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 27</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0012.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(27).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="27" id="q27_1" value="1" required>
                <label class="form-check-label" for="q27_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="27" id="q27_2" value="2" required>
                <label class="form-check-label" for="q27_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="27" id="q27_3" value="3" required>
                <label class="form-check-label" for="q27_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="27" id="q27_4" value="4" required>
                <label class="form-check-label" for="q27_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 16</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-104-0004.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(16).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="16" id="q16_1" value="1" required>
                <label class="form-check-label" for="q16_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="16" id="q16_2" value="2" required>
                <label class="form-check-label" for="q16_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="16" id="q16_3" value="3" required>
                <label class="form-check-label" for="q16_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="16" id="q16_4" value="4" required>
                <label class="form-check-label" for="q16_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 4</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-97-0001.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(4).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="4" id="q4_1" value="1" required>
                <label class="form-check-label" for="q4_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="4" id="q4_2" value="2" required>
                <label class="form-check-label" for="q4_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="4" id="q4_3" value="3" required>
                <label class="form-check-label" for="q4_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="4" id="q4_4" value="4" required>
                <label class="form-check-label" for="q4_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 57</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0012.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/55.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="57" id="q57_1" value="1" required>
                <label class="form-check-label" for="q57_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="57" id="q57_2" value="2" required>
                <label class="form-check-label" for="q57_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="57" id="q57_3" value="3" required>
                <label class="form-check-label" for="q57_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="57" id="q57_4" value="4" required>
                <label class="form-check-label" for="q57_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 47</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-104-0018.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/40.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="47" id="q47_1" value="1" required>
                <label class="form-check-label" for="q47_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="47" id="q47_2" value="2" required>
                <label class="form-check-label" for="q47_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="47" id="q47_3" value="3" required>
                <label class="form-check-label" for="q47_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="47" id="q47_4" value="4" required>
                <label class="form-check-label" for="q47_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 28</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0014.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(28).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="28" id="q28_1" value="1" required>
                <label class="form-check-label" for="q28_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="28" id="q28_2" value="2" required>
                <label class="form-check-label" for="q28_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="28" id="q28_3" value="3" required>
                <label class="form-check-label" for="q28_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="28" id="q28_4" value="4" required>
                <label class="form-check-label" for="q28_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 12</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-98-0008.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(12).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="12" id="q12_1" value="1" required>
                <label class="form-check-label" for="q12_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="12" id="q12_2" value="2" required>
                <label class="form-check-label" for="q12_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="12" id="q12_3" value="3" required>
                <label class="form-check-label" for="q12_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="12" id="q12_4" value="4" required>
                <label class="form-check-label" for="q12_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 49</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-104-0022.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/43.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="49" id="q49_1" value="1" required>
                <label class="form-check-label" for="q49_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="49" id="q49_2" value="2" required>
                <label class="form-check-label" for="q49_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="49" id="q49_3" value="3" required>
                <label class="form-check-label" for="q49_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="49" id="q49_4" value="4" required>
                <label class="form-check-label" for="q49_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 53</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0006.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/51.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="53" id="q53_1" value="1" required>
                <label class="form-check-label" for="q53_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="53" id="q53_2" value="2" required>
                <label class="form-check-label" for="q53_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="53" id="q53_3" value="3" required>
                <label class="form-check-label" for="q53_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="53" id="q53_4" value="4" required>
                <label class="form-check-label" for="q53_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 15</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-104-0001.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(15).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="15" id="q15_1" value="1" required>
                <label class="form-check-label" for="q15_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="15" id="q15_2" value="2" required>
                <label class="form-check-label" for="q15_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="15" id="q15_3" value="3" required>
                <label class="form-check-label" for="q15_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="15" id="q15_4" value="4" required>
                <label class="form-check-label" for="q15_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 29</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0018.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(29).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="29" id="q29_1" value="1" required>
                <label class="form-check-label" for="q29_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="29" id="q29_2" value="2" required>
                <label class="form-check-label" for="q29_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="29" id="q29_3" value="3" required>
                <label class="form-check-label" for="q29_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="29" id="q29_4" value="4" required>
                <label class="form-check-label" for="q29_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 8</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-98-0002.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(8).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="8" id="q8_1" value="1" required>
                <label class="form-check-label" for="q8_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="8" id="q8_2" value="2" required>
                <label class="form-check-label" for="q8_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="8" id="q8_3" value="3" required>
                <label class="form-check-label" for="q8_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="8" id="q8_4" value="4" required>
                <label class="form-check-label" for="q8_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 24</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0007.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(24).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="24" id="q24_1" value="1" required>
                <label class="form-check-label" for="q24_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="24" id="q24_2" value="2" required>
                <label class="form-check-label" for="q24_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="24" id="q24_3" value="3" required>
                <label class="form-check-label" for="q24_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="24" id="q24_4" value="4" required>
                <label class="form-check-label" for="q24_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 20</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-104-0025.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(20).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="20" id="q20_1" value="1" required>
                <label class="form-check-label" for="q20_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="20" id="q20_2" value="2" required>
                <label class="form-check-label" for="q20_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="20" id="q20_3" value="3" required>
                <label class="form-check-label" for="q20_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="20" id="q20_4" value="4" required>
                <label class="form-check-label" for="q20_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 58</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0014.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/56.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="58" id="q58_1" value="1" required>
                <label class="form-check-label" for="q58_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="58" id="q58_2" value="2" required>
                <label class="form-check-label" for="q58_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="58" id="q58_3" value="3" required>
                <label class="form-check-label" for="q58_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="58" id="q58_4" value="4" required>
                <label class="form-check-label" for="q58_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 1</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-96-0006.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(1).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="1" id="q1_1" value="1" required>
                <label class="form-check-label" for="q1_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="1" id="q1_2" value="2" required>
                <label class="form-check-label" for="q1_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="1" id="q1_3" value="3" required>
                <label class="form-check-label" for="q1_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="1" id="q1_4" value="4" required>
                <label class="form-check-label" for="q1_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 3</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-96-0008.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(3).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="3" id="q3_1" value="1" required>
                <label class="form-check-label" for="q3_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="3" id="q3_2" value="2" required>
                <label class="form-check-label" for="q3_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="3" id="q3_3" value="3" required>
                <label class="form-check-label" for="q3_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="3" id="q3_4" value="4" required>
                <label class="form-check-label" for="q3_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 48</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-104-0021.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/42.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="48" id="q48_1" value="1" required>
                <label class="form-check-label" for="q48_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="48" id="q48_2" value="2" required>
                <label class="form-check-label" for="q48_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="48" id="q48_3" value="3" required>
                <label class="form-check-label" for="q48_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="48" id="q48_4" value="4" required>
                <label class="form-check-label" for="q48_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 13</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-103-0006.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(13).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="13" id="q13_1" value="1" required>
                <label class="form-check-label" for="q13_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="13" id="q13_2" value="2" required>
                <label class="form-check-label" for="q13_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="13" id="q13_3" value="3" required>
                <label class="form-check-label" for="q13_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="13" id="q13_4" value="4" required>
                <label class="form-check-label" for="q13_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 60</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0026.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/60.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="60" id="q60_1" value="1" required>
                <label class="form-check-label" for="q60_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="60" id="q60_2" value="2" required>
                <label class="form-check-label" for="q60_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="60" id="q60_3" value="3" required>
                <label class="form-check-label" for="q60_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="60" id="q60_4" value="4" required>
                <label class="form-check-label" for="q60_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 5</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-97-0003.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(5).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="5" id="q5_1" value="1" required>
                <label class="form-check-label" for="q5_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="5" id="q5_2" value="2" required>
                <label class="form-check-label" for="q5_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="5" id="q5_3" value="3" required>
                <label class="form-check-label" for="q5_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="5" id="q5_4" value="4" required>
                <label class="form-check-label" for="q5_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 11</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-98-0005.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(11).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="11" id="q11_1" value="1" required>
                <label class="form-check-label" for="q11_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="11" id="q11_2" value="2" required>
                <label class="form-check-label" for="q11_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="11" id="q11_3" value="3" required>
                <label class="form-check-label" for="q11_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="11" id="q11_4" value="4" required>
                <label class="form-check-label" for="q11_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 46</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-104-0004.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/37.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="46" id="q46_1" value="1" required>
                <label class="form-check-label" for="q46_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="46" id="q46_2" value="2" required>
                <label class="form-check-label" for="q46_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="46" id="q46_3" value="3" required>
                <label class="form-check-label" for="q46_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="46" id="q46_4" value="4" required>
                <label class="form-check-label" for="q46_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 54</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0007.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/52.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="54" id="q54_1" value="1" required>
                <label class="form-check-label" for="q54_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="54" id="q54_2" value="2" required>
                <label class="form-check-label" for="q54_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="54" id="q54_3" value="3" required>
                <label class="form-check-label" for="q54_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="54" id="q54_4" value="4" required>
                <label class="form-check-label" for="q54_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 36</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-97-0014.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/18.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="36" id="q36_1" value="1" required>
                <label class="form-check-label" for="q36_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="36" id="q36_2" value="2" required>
                <label class="form-check-label" for="q36_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="36" id="q36_3" value="3" required>
                <label class="form-check-label" for="q36_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="36" id="q36_4" value="4" required>
                <label class="form-check-label" for="q36_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 22</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0002.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(22).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="22" id="q22_1" value="1" required>
                <label class="form-check-label" for="q22_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="22" id="q22_2" value="2" required>
                <label class="form-check-label" for="q22_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="22" id="q22_3" value="3" required>
                <label class="form-check-label" for="q22_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="22" id="q22_4" value="4" required>
                <label class="form-check-label" for="q22_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 51</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0001.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/48.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="51" id="q51_1" value="1" required>
                <label class="form-check-label" for="q51_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="51" id="q51_2" value="2" required>
                <label class="form-check-label" for="q51_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="51" id="q51_3" value="3" required>
                <label class="form-check-label" for="q51_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="51" id="q51_4" value="4" required>
                <label class="form-check-label" for="q51_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 43</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-103-0006.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/34.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="43" id="q43_1" value="1" required>
                <label class="form-check-label" for="q43_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="43" id="q43_2" value="2" required>
                <label class="form-check-label" for="q43_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="43" id="q43_3" value="3" required>
                <label class="form-check-label" for="q43_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="43" id="q43_4" value="4" required>
                <label class="form-check-label" for="q43_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 25</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0010.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(25).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="25" id="q25_1" value="1" required>
                <label class="form-check-label" for="q25_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="25" id="q25_2" value="2" required>
                <label class="form-check-label" for="q25_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="25" id="q25_3" value="3" required>
                <label class="form-check-label" for="q25_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="25" id="q25_4" value="4" required>
                <label class="form-check-label" for="q25_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 35</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-97-0003.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/5.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="35" id="q35_1" value="1" required>
                <label class="form-check-label" for="q35_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="35" id="q35_2" value="2" required>
                <label class="form-check-label" for="q35_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="35" id="q35_3" value="3" required>
                <label class="form-check-label" for="q35_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="35" id="q35_4" value="4" required>
                <label class="form-check-label" for="q35_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 17</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-104-0018.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(17).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="17" id="q17_1" value="1" required>
                <label class="form-check-label" for="q17_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="17" id="q17_2" value="2" required>
                <label class="form-check-label" for="q17_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="17" id="q17_3" value="3" required>
                <label class="form-check-label" for="q17_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="17" id="q17_4" value="4" required>
                <label class="form-check-label" for="q17_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 38</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-98-0002.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/23.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="38" id="q38_1" value="1" required>
                <label class="form-check-label" for="q38_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="38" id="q38_2" value="2" required>
                <label class="form-check-label" for="q38_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="38" id="q38_3" value="3" required>
                <label class="form-check-label" for="q38_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="38" id="q38_4" value="4" required>
                <label class="form-check-label" for="q38_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 41</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-98-0005.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/26.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="41" id="q41_1" value="1" required>
                <label class="form-check-label" for="q41_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="41" id="q41_2" value="2" required>
                <label class="form-check-label" for="q41_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="41" id="q41_3" value="3" required>
                <label class="form-check-label" for="q41_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="41" id="q41_4" value="4" required>
                <label class="form-check-label" for="q41_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 14</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-103-0007.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(14).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="14" id="q14_1" value="1" required>
                <label class="form-check-label" for="q14_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="14" id="q14_2" value="2" required>
                <label class="form-check-label" for="q14_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="14" id="q14_3" value="3" required>
                <label class="form-check-label" for="q14_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="14" id="q14_4" value="4" required>
                <label class="form-check-label" for="q14_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 55</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0010.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/53.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="55" id="q55_1" value="1" required>
                <label class="form-check-label" for="q55_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="55" id="q55_2" value="2" required>
                <label class="form-check-label" for="q55_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="55" id="q55_3" value="3" required>
                <label class="form-check-label" for="q55_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="55" id="q55_4" value="4" required>
                <label class="form-check-label" for="q55_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 10</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-98-0004.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(10).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="10" id="q10_1" value="1" required>
                <label class="form-check-label" for="q10_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="10" id="q10_2" value="2" required>
                <label class="form-check-label" for="q10_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="10" id="q10_3" value="3" required>
                <label class="form-check-label" for="q10_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="10" id="q10_4" value="4" required>
                <label class="form-check-label" for="q10_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 7</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-98-0001.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(7).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="7" id="q7_1" value="1" required>
                <label class="form-check-label" for="q7_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="7" id="q7_2" value="2" required>
                <label class="form-check-label" for="q7_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="7" id="q7_3" value="3" required>
                <label class="form-check-label" for="q7_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="7" id="q7_4" value="4" required>
                <label class="form-check-label" for="q7_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 44</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-103-0007.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/35.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="44" id="q44_1" value="1" required>
                <label class="form-check-label" for="q44_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="44" id="q44_2" value="2" required>
                <label class="form-check-label" for="q44_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="44" id="q44_3" value="3" required>
                <label class="form-check-label" for="q44_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="44" id="q44_4" value="4" required>
                <label class="form-check-label" for="q44_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 21</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0001.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(21).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="21" id="q21_1" value="1" required>
                <label class="form-check-label" for="q21_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="21" id="q21_2" value="2" required>
                <label class="form-check-label" for="q21_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="21" id="q21_3" value="3" required>
                <label class="form-check-label" for="q21_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="21" id="q21_4" value="4" required>
                <label class="form-check-label" for="q21_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 45</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-104-0001.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/36.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="45" id="q45_1" value="1" required>
                <label class="form-check-label" for="q45_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="45" id="q45_2" value="2" required>
                <label class="form-check-label" for="q45_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="45" id="q45_3" value="3" required>
                <label class="form-check-label" for="q45_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="45" id="q45_4" value="4" required>
                <label class="form-check-label" for="q45_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 52</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-106-0002.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/49.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="52" id="q52_1" value="1" required>
                <label class="form-check-label" for="q52_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="52" id="q52_2" value="2" required>
                <label class="form-check-label" for="q52_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="52" id="q52_3" value="3" required>
                <label class="form-check-label" for="q52_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="52" id="q52_4" value="4" required>
                <label class="form-check-label" for="q52_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 9</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-98-0003.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/base30/base30_(9).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="9" id="q9_1" value="1" required>
                <label class="form-check-label" for="q9_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="9" id="q9_2" value="2" required>
                <label class="form-check-label" for="q9_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="9" id="q9_3" value="3" required>
                <label class="form-check-label" for="q9_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="9" id="q9_4" value="4" required>
                <label class="form-check-label" for="q9_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 32</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-96-0007.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/1.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="32" id="q32_1" value="1" required>
                <label class="form-check-label" for="q32_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="32" id="q32_2" value="2" required>
                <label class="form-check-label" for="q32_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="32" id="q32_3" value="3" required>
                <label class="form-check-label" for="q32_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="32" id="q32_4" value="4" required>
                <label class="form-check-label" for="q32_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 31</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-96-0006.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/0.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="31" id="q31_1" value="1" required>
                <label class="form-check-label" for="q31_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="31" id="q31_2" value="2" required>
                <label class="form-check-label" for="q31_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="31" id="q31_3" value="3" required>
                <label class="form-check-label" for="q31_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="31" id="q31_4" value="4" required>
                <label class="form-check-label" for="q31_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 
<div class="card form-group">
        <div class="card-header">Câu 40</div>
        <div class="card-body">

                <p>
                    <audio controls preload="none"  src="wavs/gt30/lien-98-0004.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

                <p>
                    <audio controls preload="none"  src="wavs/adapt30/25.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="40" id="q40_1" value="1" required>
                <label class="form-check-label" for="q40_1">1. Chắc chắn là giống nhau (Definitely the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="40" id="q40_2" value="2" required>
                <label class="form-check-label" for="q40_2">2. Có thể giống (Maybe the same)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="40" id="q40_3" value="3" required>
                <label class="form-check-label" for="q40_3">3. Có thể khác nhau (Maybe different)</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="40" id="q40_4" value="4" required>
                <label class="form-check-label" for="q40_4">4. Chắc chắn là khác (Definitely different)</label>
            </div>
        </div>
    </div>
 




<input type="text" name="formid" value="1" hidden>
            <input type="text" name="thank" value="Cảm ơn bạn một lần nữa vì đã tham gia thử nghiệm này！" hidden>
            <input class="btn btn-info btn-lg" type="submit" value="Gửi kết quả" id="submitBtn">
            <p class="text-muted">
                <small>Nếu bạn thấy không trả được khi nộp kết quả vui lòng kiểm tra lại xem bạn đã điền tên mình chưa và đã trả lời được mọi câu hỏi chưa, xin cảm ơn。</small>
            </p>
        </form>
    </div>

    <div class="container" style="padding-top: 60px;">
        <p class="text-center text-muted">&copy; Phòng Thí nghiệm tiếng nói</p>
    </div>

    <script type="text/javascript">
        function preventRepeatedSubmission() {
            document.getElementById('submitBtn').disabled = true;
            setTimeout("submitBtn.disabled=false;", 5000);
            return true;
        };
    </script>
</body>

</html>

