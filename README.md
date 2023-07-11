def valid_ip(x): 
    if x.count('.') == 3: 
        return 'IPv4'
    elif x.count(':'): 
        return 'IPv6'
    else: 
        return 'Neither'


