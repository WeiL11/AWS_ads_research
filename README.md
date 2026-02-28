# Ads Research

Research project exploring the application of large models to programmatic advertising and real-time bidding (RTB).

## AdTech RTB Workflow

```
User opens page
        │
        ▼
SSP sends impression
        │
        ▼
Ad Exchange auction
        │
        ▼
DSP predicts value
        │
        ▼
Bid Optimization
        │
        ▼
RTB auction win
        │
        ▼
Ad shown
        │
        ▼
Attribution measures effect
        │
        ▼
Verification checks fraud
        │
        ▼
Optimize ROI / eCPM
```

### Stage Descriptions

| Stage | Description |
|-------|-------------|
| **User opens page** | A user visits a publisher's webpage, triggering an ad opportunity. |
| **SSP sends impression** | The Supply-Side Platform packages the impression context (page, user signals, ad slot specs) and sends a bid request. |
| **Ad Exchange auction** | The exchange broadcasts the bid request to connected demand partners and orchestrates the auction. |
| **DSP predicts value** | Each Demand-Side Platform scores the impression — estimating click-through rate (pCTR), conversion rate (pCVR), and lifetime value. |
| **Bid Optimization** | The DSP determines the optimal bid price given budget constraints, pacing rules, and campaign objectives. |
| **RTB auction win** | The highest eligible bid wins the real-time auction (typically second-price or first-price). |
| **Ad shown** | The winning creative is rendered in the user's browser and the impression is logged. |
| **Attribution measures effect** | Post-impression and post-click signals are collected to attribute conversions back to the ad exposure. |
| **Verification checks fraud** | Third-party and in-house systems validate viewability, brand safety, and flag invalid traffic (IVT). |
| **Optimize ROI / eCPM** | Feedback loops update bidding models, audience segments, and budget allocation to maximize return on ad spend. |
