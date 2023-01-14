Backtesting de Estratégia de Trading Puramente com indicadores
-------------------------------------------------

Consiste dos seguintes indicadores

ADX: Verifica a força de uma tendência com uma média móvel própria
RSI: Verifica se o preço do ativo está acima ou a baixo do que deveria com uma média móvel própria
SSL Channels: Duas médias móveis para filtrar tendência de alta ou baixa
-------------------------------------------------

Valor de cada indicador para BTCUSDTPERP (Bitcoin USDT Perpetual Contract) - Binance
TIMEFRAME = 30m

RSI = 14
RSI sobrecomprado = 74 
RSI sobrevendido = 30
Média móvel do RSI = 14

ADX na configuração inalterada = Linha de tendência -> 31
Média móvel do ADX = 12

SSL Channels = Média móvel de 200

Take profit = 1.5

Stop loss = 2.0
--------------------------------------------------

Regras para Long
1 - Vela fecha acima dos SSL Channels
2 - RSI acima ou igual a 74, e acima da sua média móvel
3 - ADX acima da linha de tendência e acima da sua média móvel -> Essa regra vale para Short também


Regras para Short
1 - Vela fecha abaixo dos SSL Channels
2 - RSI abaixo ou igual a 30, e abaixo da sua média móvel
3 - ADX acima ou igual a linha de tendência e acima da sua média móvel -> Essa regra vale para Long também
