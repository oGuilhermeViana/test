# test

'''
classDiagram
    class User {
        <<DTO>>
        -String name
        -Account account
        -List<Feature> features
        -Card card
        -List<News> news
    }
    
    class Account {
        <<DTO>>
        -String number
        -String agency
        -float balance
        -float limit
    }
    
    class Feature {
        <<DTO>>
        -String icon
        -String description
    }
    
    class Card {
        <<DTO>>
        -String cardNumber
        -float cardLimit
    }
    
    class News {
        <<DTO>>
        -String icon
        -String description
    }
    
    User --> Account
    User --> Feature
    User --> Card
    User --> News

'''
