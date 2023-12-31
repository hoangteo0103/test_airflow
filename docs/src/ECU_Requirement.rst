
================
ECU_Requirement
================

General Overview / Document Scope
*********************************

Document Scope
**************

.. sw_req:: PUT BELOW A FIRST DESCRIPTION OF THE SCOPE FOR SOFTWARE REQUIREMENT SPECIFICATION
   :id: 629016
   :artifact_type_demo: Information


   | <put below a first description of the scope for ECU requirement
     specification>



Document Specific Glossary
**************************

.. sw_req:: PUT BELOW A DEFINITION OF FIRST GLOSSARY SPECIFIC TERMS
   :id: 629013
   :artifact_type_demo: Information


   | <put below a definition of first glossary specific terms>



System Requirements
*******************

.. sw_req:: INFOS RELEVANT FOR THE COMPLETE CHAPTER
   :id: 629017
   :artifact_type_demo: Information


   | <infos relevant for the complete chapter>
   | Note to the template:
   | - the example requirements below are independent of each other and
     are showing the different possibilities of the requirements
     structure



ECU 1st Requirement
*******************

.. sw_req:: DESCRIPTION OF THE REQUIREMENT IN REQUIREMENTS LANGUAGE
   :status: New/Changed
   :id: 629015
   :safety_level: ASIL A
   :artifact_type_demo: MO_FUNC_REQ
   :crq_demo: TH2356


   | <description of the requirement in requirements language>
   | **VEHICLE_SYSTEM_BEHAVIOUR**
   | <Optional: description of desired vehicle behaviour ("development
     target")>
   | **CONSTRAINT **
   | <Optional: constraints on the solution space for the requirement>
   | **IMPACT **
   | <Optional: description of possible cross-functional impact of the
     requirement, or impact on other components>
   | **INFO**
   | <Optional: additional informations about the requirement:
   | - know-how
   | - background
   | - HW dependencies related to the system requirement
   | - internal signals
   | - etc>
   | **ASSUMPTION**
   | <Optional: assumptions on the requirement>


   .. verify:: VERIFY629015
      :style: blue

      Test Environment:
      Test Bench/Lab-car with hardware setup
      
      Success Criteria: Verify whether the signal value is correct or not

System Non Functional Requirements
**********************************

.. sw_req:: DESCRIPTION OF THE NON FUNCTIONAL REQUIREMENT IN REQUIREMENTS LANGUAGE
   :status: New/Changed
   :id: 629014
   :safety_level: ASIL B
   :artifact_type_demo: MO_NON_FUNC_REQ
   :crq_demo: TH2356


   | <description of the non functional requirement in requirements
     language>


   .. verify:: VERIFY629014
      :style: blue

      Non Func Test Environment:
      Test Bench/Lab-car with hardware setup
      
      Success Criteria: Verify whether the signal value is correct or not
