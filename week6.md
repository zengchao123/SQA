#zengchao 13126168

1.object difference：
testing-(executable)code
defect prevention:(implementation activities)
inspection :design,code, and other software artifacts
formal verification:design/code with formal specification
fault tolerance: operational software system
failure containment:system with potential accidents

2.development activities difference:
testing- testing phase and after
defect prevention - implementation(req/spec/design/coding)
inspection-all
formal verification-design/coding
fault tolerance-in-field operation
failure containment-in-field operation

3.expertise level and background knowledge difference:
testing:low-high
defect prevention:medium-high
inspection :low-medium
formal verification:high formal training
fault tolerance: high- dynamic systems
failure containment: high  safety,embedded systems

4.defect observed and dealt with :
                    At observation         At follow-up
testing             failures               fault removal
defect prevention   errors & error sources reduced fault injection
inspection          faults                 fault removal
formal verification (absence of)faults     fault absence verified
fault tolerance     local failures         global failures avoided
failure containment accidents              hazards resolytuib & damage reduction

5.main problem type dealt with difference:
testing             dynamic failures & related faults
defect prevention   systematic errors or conceptual mistakes
inspection          static & localized faults
formal verification logical faults, indirectly
fault tolerance     operational failures in small areas
failure containment accidents and related hazards

6.defect level difference:
testing              low-medium
defect prevention    low-high(particularly pervasive problems)
inspection           medium-high
formal verification  low
fault tolerance      low
failure containment  lowest

7.Ease of result interpretation and amount of QA Alternative difference
                     Result Interpretation  Information Measurement
testing                moderate               executions & failures
defect prevention      (intangible)           experience
inspection             easy                   faults, already located
formal verification    hard                   fault absence verified
fault tolerance        hard                   (unanticipated) environmentshsages
failure containment    hard                   accident scenarios and hazards

8.Cost difference:
testing                    medium  (low - high)
defect prevention          low
inspection                 low - medium
formal verification        high
fault tolerance            high
failure containment        highest

9.General difference:
QA Alternative              Applicability             Effectiveness               cost
defect prevention           known causes              systematic problems         low
testing                     code                      occasional failures         medium
inspection                  s/w artifacts             scattered faults            low - medium
formal verification         formal spec.              fault absence               high
fault tolerance             duplication               rare-cond. failures         high
failure containment         known hazards             rare-cond. accidents        highest
