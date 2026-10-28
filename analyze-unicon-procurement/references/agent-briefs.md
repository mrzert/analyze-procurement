# Agent tasks

## Common instructions

Give each agent the role, originals and source IDs and versions, shared brief, user limits, external-search scope, this file, evidence.md, and a separate output location. Give calculations.md to S and F. Agents work only on their assigned role. They do not spawn agents, alter originals, or edit the shared report.

Each agent returns in Russian: sources read and limits; facts and coordinates; inputs and formulas; conclusions, assumptions and conflicts with status; risks with evidence, effect, level, measure and closure condition; customer questions and internal questions separately; handoffs and impact on the decision. Give brief reasons, not private reasoning. Do not retell the full package.

| Role | Model | Effort | Handoff |
| --- | --- | --- | --- |
| T: tender | gpt-6.1-sol | high | Eligibility and bid actions |
| E: engineering | gpt-6-astra | high | Quantities to S; costs to F; access and data liability to L |
| S: estimate | gpt-6.1-sol | high | Cost, VAT, coverage and uncertainty to F |
| F: finance | gpt-6-astra | high | Economics and funding to coordinator |
| L: contract | gpt-6-astra | high | Contract terms and risks to F and coordinator |
| V: reviewer | gpt-6-astra | xhigh | Findings to coordinator |

These are target settings, not proof of execution. Use them only where the environment allows model and effort selection. Record actual settings when known. The coordinator retains its current model.

## T — tender specialist

Identify customer, object, location, scope, number, lot, procedure and legal regime only when supported. Check initial price, currency, VAT, funding, eligibility, qualifications, experience, permits, memberships, bid documents and subcontract limits. Do not confirm company eligibility without company evidence. Check bid, performance and warranty security: amount, basis, form, submission and return dates. Check bid and clarification deadlines, procedure stages, work start and end, and warranty; preserve time and time zone and assess dates against the analysis date. Provide payment and funding for the project card. Send detailed economics to F and contract effects to L. Return bid actions and limits on eligibility checks.

## E — engineering specialist

Make a section matrix: diameter and type (DN, outside or inside), material, length, depth, bends, chambers, defects, pressure mode and design method. Separate existing pipe from the new construction. Check main and related work, company specialization, expansion and subcontracting without assuming resources. Cover cleaning, CCTV, preparation, acceptance tests, chambers, excavations, restoration, shutdowns, bypass and pumping, flow, duration, backup and approvals where relevant. Do not invent flow rates. Check method against condition, geometry, access and pressure; a non-pressure liner is not evidence of suitability for a pressure line. Check approvals before a method change. Identify missing survey, access, site, utilities, geology, groundwater, launch and reception, temporary works and waste data where relevant. Assess schedule against supported quantities, supply, shutdowns and resources; do not invent productivity or lead times. List site checks before a bid and required surveys.

## S — estimator

Compare specifications, drawings, bills of quantities, local and aggregate estimates, and material schedules. Identify price level, indices, factors, VAT and scope of totals. Show main work groups and materials as separate cost views with compatible bases, numerator, denominator and sources. Without cost allocation, state that cost shares cannot be calculated. Check quantities, units, rates, totals, omissions and arithmetic. Do not convert length to area, DN to actual diameter, or thickness to mass without inputs. Avoid double counting resources and inclusive rates, materials and inclusive work, line items and subtotals, or local and aggregated totals. Show unallocated remainder without inventing an allocation. Check E's potential extra work; distinguish a proven omission from an open question about an inclusive price. Customer estimate profit is not contractor profit or cost.

## F — finance specialist

First extract advance, offset and return, interim and final payments, retention, funding and payment triggers. Distinguish calendar and working days, acceptance, documents and payment. After S, E and L report, show supported material, equipment, labor, mobilization, logistics, subcontract, temporary work, overhead, finance, guarantee and tax costs; mark unknown inputs. Separate security amount, tied-up cash, return, fees and interest. Calculate cash need only with an adequate agreed cash schedule. Calculate margin only with supported revenue, sufficient cost coverage and tax basis. Otherwise explain the mechanism and missing inputs. Identify budget risks and acceptance conditions against user limits. Label scenarios; do not invent percentages.

## L — contract specialist

Review payment and final settlement; advance, security and return; penalties, interest, triggers and caps; performance and warranty security; acceptance, documents, review, rejection and corrections; price and schedule changes; extra work and approval; responsibility for data, site, utilities, access and permits; warranties, defects and unilateral termination. Return clause/source, term, contractor risk, question or proposed wording, and whether the action requires verification. Do not promise that a contract can be changed. For fixed terms consider clarification, a change to procurement documents, or risk acceptance. A legality finding needs a permitted current legal check and applicability; otherwise analyze the contract text.

## V — independent reviewer

Use the originals to check decision-critical facts first, then arithmetic and all seven sections. Check price and VAT, share denominators, double counting, price versus contractor cost, dates and payment, versions and conflicts, evidence for high risks, company capability, margin and recommendation, and links between questions and risks. Return findings with sources, corrections and status: blocks final decision, needs clarification, or editorial. If there are no findings, list the checks performed. Do not invent findings, rewrite the report, or decide for the coordinator.
