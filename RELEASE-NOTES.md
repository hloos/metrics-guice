- 3.1.0
    - Don't create MetricRegistry, HealthCheckRegistry, or JmxReporter for the user. This makes it easier to integrate with existing systems that already have instances that should be used.
    - Rename InstrumentationModule to MetricsInstrumentationModule
    - Update to SLF4J
- 3.0.2
    - Update to Metrics 3.0.2
- 3.0.1
    - Update to Jackson 2.0.2
    - Update to Metrics 3.0.1
    - Update to SLF4J 1.7.6
    - Use javax.servlet:javax.servlet-api for servlet implementation
