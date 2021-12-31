//SOAL 1
{
    "_id":"ObjectId('AAA')",
    "fullName":"lala",
    "email":"lala@gmail.com",
    "phoneNumber":"012345678797"
}

//SOAL 2
RELASI ONE TO MANY
{
    "_id":"ObjectId('BBB')",
    "fullName": "lili",
    "phoneNumber": "01234567899",
    "address": [{
        "street": "jalan abcdefg"
    }, {
        "street": "jalan hijklmn"
    }]
}

//SOAL 3
RELASI ONE TO ONE
{
    "_id":"ObjectId('CCC')",
    "productName": "kaos polos",
    "brandName": "skilshirt",
    "varian": [{
        "varianName1": "Kaos Polos Hitam",
        "color": "Hitam",
        "quantity": "12",
        "price": "Rp.99.000"
    }, {
        "varianName2": "Kaos Polos Navy",
        "color": "Navy",
        "quantity": "10",
        "price": "Rp.99.000"
    }]
}

//SOAL 4
RELASI MANY TO MANY 
{
    "_id":"ObjectId('DDD')",
    "cinemaName": "CGF",
    "films": [{
        "names": "Venom 2"
    }, {
        "names": "Spiderman No Way Home"
    }],
    "location": "Pondok Indah Mall"
}
{
    "_id":"ObjectId('EEE')",
    "cinemaName": "Cinema31",
    "films": [{
        "names": "Venom 2"
    }, {
        "names": "Spiderman No Way Home"
    }],
    "location": "Mall Kelapa Gading"
}