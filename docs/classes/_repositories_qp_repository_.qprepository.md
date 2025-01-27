> **[instagram-private-api](../README.md)**

[Globals](../README.md) / ["repositories/qp.repository"](../modules/_repositories_qp_repository_.md) / [QpRepository](_repositories_qp_repository_.qprepository.md) /

# Class: QpRepository

## Hierarchy

- [Repository](_core_repository_.repository.md)

  - **QpRepository**

## Index

### Constructors

- [constructor](_repositories_qp_repository_.qprepository.md#constructor)

### Properties

- [surfacesToQueries](_repositories_qp_repository_.qprepository.md#surfacestoqueries)
- [surfacesToTriggers](_repositories_qp_repository_.qprepository.md#surfacestotriggers)

### Methods

- [batchFetch](_repositories_qp_repository_.qprepository.md#batchfetch)
- [getCooldowns](_repositories_qp_repository_.qprepository.md#getcooldowns)

## Constructors

### constructor

\+ **new QpRepository**(`client`: [IgApiClient](_core_client_.igapiclient.md)): _[QpRepository](\_repositories_qp_repository_.qprepository.md)\_

_Inherited from [Repository](\_core_repository_.repository.md).[constructor](_core_repository_.repository.md#constructor)\_

_Defined in [core/repository.ts:6](https://github.com/realinstadude/instagram-private-api/blob/4ae8fec/src/core/repository.ts#L6)_

**Parameters:**

| Name     | Type                                        |
| -------- | ------------------------------------------- |
| `client` | [IgApiClient](_core_client_.igapiclient.md) |

**Returns:** _[QpRepository](\_repositories_qp_repository_.qprepository.md)\_

## Properties

### surfacesToQueries

• **surfacesToQueries**: _string_ = `{"5734":"viewer() {eligible_promotions.trigger_context_v2(<trigger_context_v2>).ig_parameters(<ig_parameters>).trigger_name(<trigger_name>).surface_nux_id(<surface>).external_gating_permitted_qps(<external_gating_permitted_qps>).supports_client_filters(true).include_holdouts(true) {edges {client_ttl_seconds,log_eligibility_waterfall,is_holdout,priority,time_range {start,end},node {id,promotion_id,logging_data,max_impressions,triggers,contextual_filters {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}},clauses {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}},clauses {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}},clauses {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}}}}}},is_uncancelable,template {name,parameters {name,required,bool_value,string_value,color_value,}},creatives {title {text},content {text},footer {text},social_context {text},social_context_images,primary_action{title {text},url,limit,dismiss_promotion},secondary_action{title {text},url,limit,dismiss_promotion},dismiss_action{title {text},url,limit,dismiss_promotion},image.scale(<scale>) {uri,width,height}}}}}}","5858":"viewer() {eligible_promotions.trigger_context_v2(<trigger_context_v2>).ig_parameters(<ig_parameters>).trigger_name(<trigger_name>).surface_nux_id(<surface>).external_gating_permitted_qps(<external_gating_permitted_qps>).supports_client_filters(true).include_holdouts(true) {edges {client_ttl_seconds,log_eligibility_waterfall,is_holdout,priority,time_range {start,end},node {id,promotion_id,logging_data,max_impressions,triggers,contextual_filters {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}},clauses {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}},clauses {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}},clauses {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}}}}}},is_uncancelable,template {name,parameters {name,required,bool_value,string_value,color_value,}},creatives {title {text},content {text},footer {text},social_context {text},social_context_images,primary_action{title {text},url,limit,dismiss_promotion},secondary_action{title {text},url,limit,dismiss_promotion},dismiss_action{title {text},url,limit,dismiss_promotion},image.scale(<scale>) {uri,width,height}}}}}}","4715":"viewer() {eligible_promotions.trigger_context_v2(<trigger_context_v2>).ig_parameters(<ig_parameters>).trigger_name(<trigger_name>).surface_nux_id(<surface>).external_gating_permitted_qps(<external_gating_permitted_qps>).supports_client_filters(true).include_holdouts(true) {edges {client_ttl_seconds,log_eligibility_waterfall,is_holdout,priority,time_range {start,end},node {id,promotion_id,logging_data,max_impressions,triggers,contextual_filters {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}},clauses {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}},clauses {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}},clauses {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}}}}}},is_uncancelable,template {name,parameters {name,required,bool_value,string_value,color_value,}},creatives {title {text},content {text},footer {text},social_context {text},social_context_images,primary_action{title {text},url,limit,dismiss_promotion},secondary_action{title {text},url,limit,dismiss_promotion},dismiss_action{title {text},url,limit,dismiss_promotion},image.scale(<scale>) {uri,width,height}}}}}}"}`

_Defined in [repositories/qp.repository.ts:26](https://github.com/realinstadude/instagram-private-api/blob/4ae8fec/src/repositories/qp.repository.ts#L26)_

---

### surfacesToTriggers

• **surfacesToTriggers**: _string_ = `{"5734":["instagram_feed_prompt"],"5858":["instagram_feed_tool_tip"],"4715":["instagram_feed_header"]}`

_Defined in [repositories/qp.repository.ts:27](https://github.com/realinstadude/instagram-private-api/blob/4ae8fec/src/repositories/qp.repository.ts#L27)_

## Methods

### batchFetch

▸ **batchFetch**(): _`Promise<object & object>`_

_Defined in [repositories/qp.repository.ts:10](https://github.com/realinstadude/instagram-private-api/blob/4ae8fec/src/repositories/qp.repository.ts#L10)_

**Returns:** _`Promise<object & object>`_

---

### getCooldowns

▸ **getCooldowns**(): _`Promise<object & object>`_

_Defined in [repositories/qp.repository.ts:4](https://github.com/realinstadude/instagram-private-api/blob/4ae8fec/src/repositories/qp.repository.ts#L4)_

**Returns:** _`Promise<object & object>`_
