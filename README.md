
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>kalkulator by: M. Rasyid A.G</title>
    <link rel="stylesheet" href="css/style17.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css">
</head>

<body data-theme="">
    <div class="calculator">
        <div class="result-container">
            <input type="text" class="result-input result-input-kecil" disabled value="0">
            <input type="text" class="result-input result-input-besar" disabled value="0">
        </div>
        <div class="body-calculator">
            <div class="item-calculator-container">
                <div class="delete-result-container">
                    <div class="item remove-all-item">AC</div>
                    <div class="item remove-one-item">DEL</div>
                    <div class="item item-red item-red-2" data-value="/100">%</div>
                    <div class="item item-red operator-item" data-value="/">&#247;</div>
                </div>
                <div class="number-calculator-container">
                    <div class="item number-item" data-value="7">7</div>
                    <div class="item number-item" data-value="8">8</div>
                    <div class="item number-item" data-value="9">9</div>
                    <div class="item item-red operator-item" data-value="*">&#215;</div>
                    <div class="item number-item" data-value="4">4</div>
                    <div class="item number-item" data-value="5">5</div>
                    <div class="item number-item" data-value="6">6</div>
                    <div class="item item-red operator-item" data-value="-">-</div>
                    <div class="item number-item" data-value="1">1</div>
                    <div class="item number-item" data-value="2">2</div>
                    <div class="item number-item" data-value="3">3</div>
                    <div class="item item-red operator-item" data-value="+">+</div>
                    <div class="item number-item" data-value="0">0</div>
                    <div class="item number-item" data-value="00">00</div>
                    <div class="item number-item" data-value="000">000</div>
                    <div class="item item-red-1 result-item" data-value="">=</div>
                </div>
            </div>
        </div>
        <div class="theme-container">
            <div class="light-theme" title="Change Light Mode">
                <div class="btn-theme btn-light-theme far fa-sun"></div>
            </div>
            <div class="dark-theme" title="Change Dark Mode">
                <div class="btn-theme btn-dark-theme far fa-moon"></div>
            </div>
        </div>
        <div class="btn-copy" title="Copy Result">
            <div class="far fa-clipboard"></div>
        </div>
        <div class="btn-riwayat" title="History">
            <span class="fas fa-history"></span>
        </div>
    </div>
    <footer>
        © FOLLOW INSTAGRAM 
        <a href="https://www.instagram.com/syidxzzz/" target="_blank">@Syidxzzz</a>
        😉🤟
    </footer>
    <div class="riwayat-container">
        <div class="riwayat-box">
            <div class="header-riwayat">
                <div class="header-riwayat-txt">History</div>
                <div class="close-riwayat">
                    <div class="fas fa-times"></div>
                </div>
            </div>
            <div class="body-riwayat">Belum Ada Riwayat</div>
            <div class="footer-riwayat">
                <div class="btn-trash">
                    <div class="far fa-trash-alt"></div>
                </div>
            </div>
        </div>
    </div>
    
    <script src="js/script3.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/js/all.min.js"></script>
</body>

</html>
