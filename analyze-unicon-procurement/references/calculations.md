# Cost and finance

For each figure retain the source, currency, date and price level, unit, VAT, object and cost scope. Separate initial or maximum price, bid price, contract price, estimate and contractor cost. The initial price is not guaranteed revenue. Calculate with a calculator, spreadsheet or Python Decimal; retain inputs and formulas. Round only for final presentation and do not imply greater precision than the inputs. Unknown is not zero. State coverage and unchecked portions; do not call incomplete totals complete.

## Cost shares

On compatible bases: `work share (%) = work group cost / contract price × 100`; `material share (%) = material cost / contract price × 100`. If there is no contract, use a supported initial price or estimate total and name that denominator. Do not call it a share of an unknown bid price. Do not divide an ex-VAT amount by an inc-VAT total. Convert only with supported tax rates and scope. For a confirmed single rate r: `ex-VAT price = inc-VAT price / (1 + r)`; calculate mixed rates per item.

Work and materials are separate views and may overlap; never add their shares. Do not add resources to inclusive rates, items to subtotals, or local to aggregate estimates. State aggregation level. If resource costs and contract prices cannot be reconciled, report the available resource breakdown and say that contract shares cannot be established. For incomplete breakdowns, `total = known non-overlapping groups + unallocated remainder`; investigate a negative remainder. Do not substitute length, item count or labor shares for cost shares; label such additional views separately.

## Margin

Define the metric. Preliminary project margin `M = (R − C) / R × 100`, where R is supported revenue on an agreed basis and C is applicable cost with disclosed coverage. State excluded finance or overhead costs; do not call this net profit. For a VAT payer, exclude output VAT from revenue and only confirmed recoverable input VAT from costs. Retain non-recoverable tax in costs. Do not assume tax status or recovery; do not calculate final margin without the tax basis. Distinguish margin `(R − C) / R` from markup `(R − C) / C`. Disclose direct and indirect costs, finance, fees, warranty costs and supported reserves; do not invent reserves.

For a user-specified target margin m and complete C, with `0 ≤ m < 1`, `minimum revenue = C / (1 − m)`. State scope and applicability. Without m or complete C, do not invent a minimum price or discount limit. A price remainder after partial costs is not profit. Customer estimate profit and overhead do not prove contractor profitability.

## Cash and security

Separate the obligation amount, temporarily tied-up cash and non-refundable cost. Record cash security as a payment and return in cash flow, not final cost. A bank guarantee does not automatically tie up its full amount; check fee, collateral and dates. Retention delays cash but does not by itself reduce revenue or create an expense.

With a supported schedule: `flow_t = receipts_t − payments_t`; `cumulative_t = sum of flows through t`; `funding need before available cash = max(0, −min(cumulative_t))`. Only if starting funds B are known: `remaining need = max(0, −min(B + cumulative_t))`. Do not count credit as both coverage and proof of no funding need.

Tie receipts to contractual acceptance, documents, advance offsets, retention and final settlement. Place security returns and funding on their relevant dates. Use one VAT basis for cash flows; margin may need a different tax presentation. Without dates, purchases or payment terms, explain the mechanism and missing inputs instead of calculating a precise gap. Keep `N days after event` conditional until the event date is known. Do not convert working days into a date without a confirmed calendar.
