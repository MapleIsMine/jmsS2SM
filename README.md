版本11:
   完成基于activemq的yi步邮件发送服务.
   
   
实现需求:
    1。 在EmailAdvice的sendEmailMethod()方法中调用消息生产者发送一个消息(客户只要进行了存，取，转账业务)，传送到 activemq服务器
    2. 传送的消息是TextMessage, 所以要将对象转换成 字符串发送. 