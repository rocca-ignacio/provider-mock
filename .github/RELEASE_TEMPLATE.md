<details>
<summary><h2>📋 Release Summary</h2></summary>

### Description
<!-- Brief description of changes. Include modified services and key functionalities added/updated -->


### Affected Services
| Service | Previous Version | New Version |
|---------|-----------------|-------------|
|         |                 |             |

---

### Rollback Plan 🔙
<!-- Fill in for each affected service -->
```
Rollback [service-name] to version [previous-version]
```

---

### Pre-Deploy Checklist ✅
> Add screenshot/evidence for each applicable check

- [ ] New environment variables configured in **PROD**
- [ ] Database migrations reviewed and tested (if applicable)
- [ ] Feature flags configured (if applicable)
- [ ] Kafka topic/consumer changes verified (if applicable)
- [ ] Backward compatibility confirmed (API contracts, events)
- [ ] Load/performance impact assessed

---

### Real-Time Monitoring 📊
> Add screenshot for each check. For canary deployments, include evidence for all monitored stages.

**Datadog Dashboards:**

- [ ] **Service APM**
  <!-- [Insert screenshot] -->

- [ ] **Service Error Rate**
  <!-- [Insert screenshot] -->

- [ ] **Latency (p50 / p95 / p99)**
  <!-- [Insert screenshot] -->

- [ ] **Pod Health / Restarts**
  <!-- [Insert screenshot] -->

- [ ] **Logs (errors, warnings)**
  <!-- [Insert screenshot] -->

- [ ] **Kafka Consumer Lag** (if applicable)
  <!-- [Insert screenshot] -->

- [ ] **Database Connections / Query Performance** (if applicable)
  <!-- [Insert screenshot] -->

---

### Anomalies 🚨
<!-- If any anomalies are detected post-deploy, document them here with relevant context -->
None observed.

---

### Sign-off
| Role | Name | Status |
|------|------|--------|
| Deployer | | ✅ / ❌ |
| Reviewer | | ✅ / ❌ |

</details>
