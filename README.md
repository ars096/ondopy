# おんどとり TR-71/72nw 通信 python モジュール

## インストール

`pip install ondopy`


## 使用例

    import ondopy
    
    host = '192.168.1.10'
    serial_number = '5214abcd'
    
    t = ondopy.tr7nw(host, serial_number)
    t.get_current()
    >>> [{'unit': 'C', 'value': 23.5}, {'unit': '%', 'value': 50.099999999999994}]

