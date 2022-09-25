# Dubbo 责任链模式

## 生产者过滤器链路
EchoFilter > ClassloaderFilter > GenericFilter > ContextFilter >
TraceFilter > TimeoutFilter > MonitorFilter > ExceptionFilter > AbstractProxyInvoker

## 消费者过滤器链路
ConsumerContextFilter > FutureFilter > MonitorFilter > DubboInvoker
