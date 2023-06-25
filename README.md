# 短信收纳大师短信数据 classified_sms_messages

数据标记方法
```
   /// Insufficient information to determine an action to take. In a query response, has the effect of allowing the message to be shown normally.
    case none = 0

    
    /// Allow the message to be shown normally.
    case allow = 1

    
    /// Prevent the message from being shown normally, filtered as Junk message.
    case junk = 2

    /// Prevent the message from being shown normally, filtered as Junk message.
    @available(iOS, introduced: 11.0, deprecated: 14.0, renamed: "ILMessageFilterAction.junk")
    public static var filter: ILMessageFilterAction { get }

    
    /// Prevent the message from being shown normally, filtered as Promotional message.
    @available(iOS 14.0, *)
    case promotion = 3

    
    /// Prevent the message from being shown normally, filtered as Transactional message.
    @available(iOS 14.0, *)
    case transaction = 4
```


```
  /// Insufficient information to determine an action to take. In a query response, has the effect of allowing the message to be shown normally.
    case none = 0

    
    /// TRANSACTIONAL SUB-ACTIONS
    
    /// Prevent the message from being shown normally, filtered as Other message.
    case transactionalOthers = 10000

    
    /// Prevent the message from being shown normally, filtered as Finance message.
    case transactionalFinance = 10001

    
    /// Prevent the message from being shown normally, filtered as Orders (eCommerce) message.
    case transactionalOrders = 10002

    
    /// Prevent the message from being shown normally, filtered as Reminder message.
    case transactionalReminders = 10003

    
    /// Prevent the message from being shown normally, filtered as Health message.
    case transactionalHealth = 10004

    
    /// Prevent the message from being shown normally, filtered as Weather message.
    case transactionalWeather = 10005

    
    /// Prevent the message from being shown normally, filtered as Carrier message.
    case transactionalCarrier = 10006

    
    /// Prevent the message from being shown normally, filtered as Rewards message.
    case transactionalRewards = 10007

    
    /// Prevent the message from being shown normally, filtered as Government message.
    case transactionalPublicServices = 10008

    
    /// PROMOTIONAL SUB-ACTIONS
    
    /// Prevent the message from being shown normally, filtered as Others message.
    case promotionalOthers = 20000

    
    /// Prevent the message from being shown normally, filtered as Offers message.
    case promotionalOffers = 20001

    
    /// Prevent the message from being shown normally, filtered as Coupons message.
    case promotionalCoupons = 20002
```
