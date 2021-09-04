# stock_analysis

## 股票抓取

### URLs
* 日k (e.g. 688599)
	<pre>
	<p>URL: http://38.push2his.eastmoney.com/api/qt/stock/kline/get</p>
	params = {
		'cb'='jQuery112406967554777383818_1630682126830',
		'secid'='1.688599',
		'ut'='fa5fd1943c7b386f172d6893dbfba10b',
		'fields1'='f1%2Cf2%2Cf3%2Cf4%2Cf5%2Cf6',
		'fields2'='f51%2Cf52%2Cf53%2Cf54%2Cf55%2Cf56%2Cf57%2Cf58%2Cf59%2Cf60%2Cf61',
		'klt'='101',
		'fqt'='1',
		'end'='20500101',
		'lmt'='783',
		'_'='1630682126899'
	}
	</pre>
* 股票list
	<pre>
	<p>URL: https://eniu.com/static/data/stock_list.json</p>
	</pre>
* 基础KPI
    <pre>
    <p>URL:  http://push2.eastmoney.com/api/qt/stock/get</p>
    params = {
        'ut'='fa5fd1943c7b386f172d6893dbfba10b',
        'fltt'=2,
        'invt'=2,
        'volt'=2,
        'fields'='f43,f57,f58,f169,f170,f46,f44,f51,f168,f47,f164,f163,f116,f60,f45,f52,\
                    f50,f48,f167,f117,f71,f161,f49,f530,f135,f136,f137,f138,f139,f141,\
                    f142,f144,f145,f147,f148,f140,f143,f146,f149,f55,f62,f162,f92,f173,\
                    f104,f105,f84,f85,f183,f184,f185,f186,f187,f188,f189,f190,f191,f192,\
                    f107,f111,f86,f177,f78,f110,f262,f263,f264,f267,f268,f250,f251,f252,\
                    f253,f254,f255,f256,f257,f258,f266,f269,f270,f271,f273,f274,f275,f127,\
                    f199,f128,f198,f259,f260,f261,f171,f277,f278,f279,f288,f292,f182',
        'secid'=1.688599,
        'cb'='jQuery1124009888531732325911_1630686566674',
        '_'='1630686566675'
    }
    </pre>
* 财表
    <pre>
    <p>URL: http://emweb.eastmoney.com/PC_HSF10/NewFinanceAnalysis/lrbAjaxNew</p>
    params = {
        'companyType'=4，
        'reportDateType'=0，
        'reportType'=1，
        'dates'='2019-09-30'，
        'code'='sh688599'
    }
    </pre>
    
## 数据存储

## 股价分析