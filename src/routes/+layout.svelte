<script>
    let src = '/coffee.png';
    let name = 'logo';
</script>

<nav>
    <a href='/'>
        <img src={src} alt={name} id="logo"/>
    </a>
    <a href='/'>메인</a>
    <a href='/read'>레시피보기</a>
    <a href='/add'>레시피추가</a>
</nav>

<slot></slot>

<style>
    nav {
        display: flex;
        align-items: center;
        border-bottom: 1px solid #fff;
        width: 100vw;
        font-family: 'Noto Sans CJK KR', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    }
    a {
        color: #FACA19;
        text-decoration: none;
        font-size: 2vw;
        margin-right: 2vw;
    }
    #logo {
        width: 4vw;
        height: 4vw;
        margin-left: 3vw;
        margin-right: 2.5vw;
    }
</style>