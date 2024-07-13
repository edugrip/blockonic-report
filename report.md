# Project Status Report

## Extra Work Done

1. **Completed the new design**
2. **New implementation of orderbook** 
   - Due to move from Java to Node.js as required
3. **Kafka server setup pipelines**
   - Previously using ring buffer and disruptor
4. **New implementation of backend**
5. **Application Development**
   - Balance Management APIs
   - Failover Plan Update
   - Kafka config and performance optimizations with Topics
   - Order engine speed optimizations
   - Balance retrieval speed optimization
6. **Authentication**
   - Social Login
   - Captcha
7. **Microservices pipeline**
8. **Disaster Management**
9. **Perpetual Futures in Order Engine**
10. **Options**
    - Worked but not feasible due to many reasons, biggest being the risk and liquidity

## Pending Work

1. **Admin Panel APIs Integration**
   - One backend, one frontend
2. **Reports**
   - Which one?
3. **APK APIs Integration**
   - Some already done (App Developer)
4. **AWS Deployment pipelines**
5. **Design Updates**
   - Feature updates if required
6. **Copy Trading**
7. **Bot Trading**

## Current Reports

### Trading Volume Report
- `trade_id`
- `timestamp`
- `pair`
- `volume` (last 24 hours)
- `price`
- `total`

### User Activity Report
- `user_id`
- `timestamp`
- `activity_type` (e.g., login, trade, withdrawal)
- `details`

### Transaction Fee Report
- `transaction_id`
- `timestamp`
- `user_id`
- `fee_amount`
- `transaction_type` (e.g., trade, withdrawal, deposit)

### Liquidity Report
- `pair`
- `timestamp`
- `bid_volume`
- `ask_volume`
- `total_liquidity`

### Withdrawal and Deposit Report
- `transaction_id`
- `user_id`
- `timestamp`
- `type` (withdrawal, deposit)
- `amount`
- `status`

### Order Book Report
- `order_id`
- `timestamp`
- `user_id`
- `pair`
- `order_type` (buy, sell)
- `price`
- `quantity`
- `status`

### Compliance Report
- `report_id`
- `timestamp`
- `user_id`
- `compliance_type` (KYC, AML)
- `status`
- `notes`

### Security Incident Report
- `incident_id`
- `timestamp`
- `user_id`
- `incident_type`
- `description`
- `resolution_status`

### Revenue Report (Work in progress)
- `revenue_id`
- `timestamp`
- `source` (trading fees, withdrawal fees, etc.)
- `amount`

### Market Depth Report (Work in progress)
- `pair`
- `timestamp`
- `bid_prices`
- `ask_prices`
- `bid_volumes`
- `ask_volumes`

### Asset Balances Report
- `user_id`
- `timestamp`
- `asset`
- `balance`

### P&L (Profit and Loss) Report
- `user_id`
- `timestamp`
- `pair`
- `trade_id`
- `pnl_amount`

### KYC/AML Compliance Report
- `user_id`
- `timestamp`
- `compliance_type` (KYC, AML)
- `status`
- `notes`

## Pending Reports

### API Usage Report
- `api_key`
- `user_id`
- `timestamp`
- `endpoint`
- `request_count`

### System Performance Report
- `report_id`
- `timestamp`
- `metric` (e.g., latency, uptime, error rate)
- `value`
- `status`

### Historical Volume Data
- (Pending)
