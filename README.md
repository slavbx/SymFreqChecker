# SymFreqChecker
REST API, предоставляющее информацию о частоте встречи символов в заданной строке

Endpoints
POST api/check-symbols

Параметры path
Отсутствуют

Параметры строки запроса
Отсутствуют

Пример запроса
POST "http://localhost:8080/api/check-symbols"
BODY: 
{
    "text": "aaaaabcccc"
}

Пример ответа
{
    "a": 5,
    "c": 4,
    "b": 1
}
