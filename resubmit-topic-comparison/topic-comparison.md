# Topic Comparison

## Before Topic Configuration

Before Topic configuration, natural-language analysis was performed using the available dataset-level Q&A/My Assistant capability. The Topic was not yet configured.

## After Topic Configuration

The NovaTech Revenue Intelligence Topic was created and published using:

- novatech_crm_deals-csv
- novatech_support_tickets-csv
- novatech_marketing_campaigns-csv

Relationships were configured using `account_id` between CRM and Marketing and between CRM and Support.

Custom instructions were added to guide distinct ID counting and metric interpretation.

After publishing the Topic, My Assistant successfully used the Topic to answer natural-language business questions.

## Comparison

Before Topic configuration, analysis relied on the available dataset-level assistance.

After Topic configuration, the NovaTech Revenue Intelligence Topic provided a semantic layer connecting the three datasets and enabled natural-language analysis across the related data.

## Reconciliation

The Topic and dashboard use the same underlying business data. Metric calculations account for one-to-many relationships in the unified dataset. Distinct identifiers are used where appropriate to avoid double counting.