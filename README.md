Hi, everyone! Today I will show you my table, and then I will show you my site, which I have not yet done with clickable buttons. Then evaluate my work)).
<html>
<head></head>
<body>
    <div class="first">
        <p>Всем привет!Дорогие поклоники футбола.</p>
        <p>Сегодня мы увидем Результаты группового этапа</p>
        <p>Лиги Чемпионов и Лиги Европы.В этом</p>
        <p>блоке Мы увидем Результаты группового</p>
        <p>этапа Лиги Европы.Вы можете увидеть
        внизу.</p>
    </div>
    <div class="second">
        <p>В данном блоке мы увидем Лиги</p>
        <p>Чемпионов.Все Результаты можно увидеть</p>
        <p>в таблице внизу.Также вскорем временем</p>
        <p>мы выпустим ещё один блок о ЧМ-2018.</p>
        <p>На этом всё до скорой встречи.</p>
    </div>
        <table>
            <tr>
                <th class="center" colspan="7">Лига Европы</th>
            </tr>
            <tr>
                <th>Места</th>
                <th>Футбольные клубы</th>
                <th>Количество Побед/Ничей/Поражений</th>
                <th>Количество забитых/пропущенных голов</th>
                <th>Очки</th>
            </tr>
            <tr>
                <th>1</th>
                <th>Зенит</th>
                <th>4/2/0</th>
                <th>12/6</th>
                <th>14</th>
            </tr>
            <tr>
                <th>2</th>
                <th>Копенгаген</th>
                <th>2/2/2</th>
                <th>5/4</th>
                <th>8</th>
            </tr>
            <tr>
                <th>3</th>
                <th>Славия</th>
                <th>1/3/2</th>
                <th>5/7</th>
                <th>6</th>
            </tr>
            <tr>
                <th>4</th>
                <th>Бордо</th>
                <th>0/2/4</th>
                <th>6/12</th>
                <th>2</th>
            </tr>
        </table>
            <table class="Liga">
            <tr>
            <th class="center" colspan="7">Лига Чемпионов</th>
            </tr>
            <tr>
                    <th>Места</th>
                    <th>Футбольные клубы</th>
                    <th>Количество Побед/Ничей/Поражений</th>
                    <th>Количество забитых/пропущенных голов</th>
                    <th>Очки</th>
                </tr>
            <tr>
                <th>1</th>
                <th>Реал Мадрид</th>
                <th>3/1/2</th>
                <th>11/7</th>
                <th>10</th>
            </tr>
            <tr>
                <th>2</th>
                <th>Рома</th>
                <th>3/1/2</th>
                <th>10/9</th>
                <th>10</th>
            </tr>
            <tr>
                <th>3</th>
                <th>ЦСКА</th>
                <th>2/1/3</th>
                <th>7/6</th>
                <th>7</th>
            </tr>
            <tr>
                <th>4</th>
                <th>Виктория</th>
                <th>0/1/5</th>
                <th>6/15</th>
                <th>1</th>
            </tr>
        </table>
    </div>
</body>
</html>

<style>
* {
   padding: 0;
   margin: 0;
    }
.first {
    width: 200px;
    border: 1px solid green;
    padding: 20px;
    margin-left: 50px;
    margin-top: 40px;
    float: left;
}
.second {
    width: 300px;
    border: 1px solid red;
    margin-top: 40px;
    margin-left: 20px;
    display: inline-block;
}
.first:hover {
    width: 400px;
    color: goldenrod;
    cursor: pointer;
    font-size: 30px;
    border: 3px solid burlywood;
}
.second:hover {
    width: auto;
    text-align: right;
    padding: 20px;
    font-size: 25px;
    color: darkcyan;
    border: 4px solid cornflowerblue;
}
p:first-child {
    color: red;
}
p:last-child {
    color: darkcyan
}
p:nth-of-type(2) {
    color: blue
}
td {
    border: 2px solid black;
    color: darkcyan;
    font-size: 14px;
}
th.center {
    text-align: center;
}
th {
    border: 2px solid black;
    font-size: 20px;
}
th {
    width: 200px;
    margin-top: 20px;
    margin-left: 20px;
    border: 2px solid black;
    
}
th:hover {
    width: auto;
    text-align: center;
    padding: 20px;
    font-size: 25px;
    color: darkcyan;
    border: 4px solid goldenrod;
}
table {
    border: 5px solid darkgoldenrod;
    border-collapse: collapse;
    text-align: center;
    width: 200px;
    margin-top: 10px;
    margin-left: 110px;
    font-size: 20px;
}
.Liga:hover {
    width: 200px;
    color: goldenrod;
    cursor: pointer;
    font-size: 500px;
    padding:100px;
    border: 10px solid burlywood;
}
.Liga {
    border: 5px solid goldenrod;
    border-collapse: collapse;
    text-align: center;
    width: 500px;
    margin-top: 0px;
    margin-left: 50px;
}
tr {
    border-bottom: 1px solid black;
    background-color: darkgreen;
    color: darkcyan;
}
div>p {
    color:darkorange; 
}
</style>
