# spring-notes

```
//https://www.concretepage.com/spring/spring-component-scan-include-and-exclude-filter-example
@ComponentScan( excludeFilters={
    @ComponentScan.Filter(type= FilterType.ASSIGNABLE_TYPE, value=TransactionLoggingRequestInterceptor.class)})
    
```
