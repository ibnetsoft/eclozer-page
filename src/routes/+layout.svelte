<aside>
    <section class="header-bar">
        <div class="hb-logo">
            <img src="images/eclozer-logo-white.png" alt="">
        </div>
    </section>
</aside>

<slot />

<footer id="main-footer">
    <section class="footer">
        <div id="footer-logo">
            <img src="images/eclozer-logo-white.png" alt="회사 로고">
        </div>
        <div class="company">
            <div class="company-title">이클로저</div>
            <div>사업자 등록번호 : 444-48-00221</div>
            <div>대표이사 : 김세현</div>
            <div>주소 : 서울시 강남구 역삼로 29길 19</div>
            <div>연락처 :  070-8648-1179</div>
        </div>
        <div class="copy">
            <p>© 2023 Copyright by ECLOZER</p>
        </div>  
    </section>
</footer>


<style>
    aside{
        position: relative;
        background-color: black;
    }
    .header-bar{
        width: 100%;
        height: 50px;
        background-color: black;
        opacity: 0.2;
        margin: 0 auto;
        position: fixed;
        overflow: hidden;
        
    }
    .hb-logo{
        width: 150px;
        background-color: black;
    }
    .hb-logo img{
        width: 100%;
       
    }

    #main-footer{
    height: auto;
    display: flex;
    justify-content: right;
    background-color: #000;
    padding:  0 5%;
    color: #fff;
}

.footer{
    width: 60%;
    margin: 0 auto;
    display: flex;
    flex-flow: column;
    justify-content: space-between;
    align-items: center;
    font-size: 0.5rem;
    color: lightgrey;
}

#footer-logo{
    margin: 1rem 4rem;
    height: 3.5rem;
    margin-bottom: 2rem;
}

#footer-logo img{
    height: 4.5rem;
}

/* .company{
    margin-left: 4rem;
} */
.company div{
    font-size: 13px;
    text-align: center;
    /* margin-top: 1rem; */
    padding: 0.2rem;
}


.copy{
    margin: 2rem 0;
    text-align: center;
}

@media (max-width:628px){
    #footer-logo img{
        margin: 1rem;
        height: 3.5rem;
        margin-left: 0;
    }
    .company{
        margin-left: 0;
    }
     .company div{
        font-size: 12px;
    }

    .copy{
        margin: 0;
        padding: 0;
    }
}

@media (max-width: 375px){
    #footer-logo img{
        margin: 1rem;
        height: 3.5rem;
        margin-left: 0;
    }
    .company{
        margin-left: 0;
    }

    .company div{
        font-size: 12px;
    }

    .copy{
        margin: 0;
        padding: 0;
    }
}


</style>


