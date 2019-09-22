### Ildar Garifullin
ildar107wk@gmail.com 
8-963-144-21-88

I am c# software developer with 2+ years experience.
My goal is to improve my professional skills in order to get a more interesting and complex project / work.

### Skills 
* C#
* SQL
* JS
* ASP.NET WebForms
* ASP.NET MVC
* Entiity Framework
* SVN
* Git
* JQuery
* Bootstrap

### Code Example
```javascript
function getCreditLimit() {
    preloader.showPreloader();
    $.ajax({
        type: "POST",
        url: "Create_Request.aspx/GetCreditLimit",
        data: JSON.stringify({contractCode: ITRequestInitialData.contractCode}),
        contentType: "application/json; charset=utf-8",
        dataType: "json",
        success: function (output) {
            var config = output.d;
            //console.log(config);
            preloader.hidePreloader();

            ITRequestInitialData.balance = config.Balance;
            ITRequestInitialData.creditLimit = config.CreditLimit;
            ITRequestInitialData.overDue = config.OverDue;
            ITRequestInitialData.overDueDays = config.OverDueDays;
            ITRequestInitialData.receivables = config.Receivables;
            ITRequestInitialData.productCart = cart.items;
            $('input[name="ctl00$MainContent$DataForITRequest"]').val("");
            $('input[name="ctl00$MainContent$DataForITRequest"]').val(JSON.stringify(ITRequestInitialData));
            $('input[name="ctl00$MainContent$openRequestEdit"]').click();
        },
        error: function (xhr, status, error) {
            preloader.hidePreloader();
            HandlerAJAXError(xhr, status, error, function () {
                history.back();
            });
        }
    });
} 
```

### Experience

July 2017 — november 2018  <br>[Аплана БР](http://www.it.ru/)  <br>C# fullstack developer

1. Developing CRM system on  bpm'online (C#, js).
1. Developing Web-application (ASP.NET WebForms)


November 2018 — currently<br>  [I-Teco Company](https://www.i-teco.ru/)<br> C# developer

1. Developing Web-application for bank system(Silverlight)

### Education

 Higher education:
 * USATU Computer science master degree

 Online Course:
 * https://ulearn.me/ - entire c# course
 * https://ulearn.me/ - LINQ course

### English
I participated in a marathon from [Lingoda](https://www.lingoda.com/ru/). It's 1 lesson (during 1 hour) per day for 3 months. Also everyday I need read a lot of information in English cause it's nessery for my work.
