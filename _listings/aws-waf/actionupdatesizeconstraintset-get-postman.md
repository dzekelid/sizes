{
  "info": {
    "name": "AWS WAF API Update Size Constraint Set",
    "_postman_id": "93b420cf-f089-4c79-b41e-028e4b176a6a",
    "description": "Service: AWS WAFInserts or deletes.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Web ACL",
      "item": [
        {
          "id": "9eb2d8af-2d72-45d1-a993-8b2e2ce7780b",
          "name": "associateWebACL",
          "request": {
            "url": "http://example.com/api/?Action=AssociateWebACL?ResourceArn=ResourceArn&WebACLId=WebACLId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAF RegionalAssociates a web ACL with a resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15b0e7f0-e5b4-47f6-832e-708b20d1abaf"
            }
          ]
        },
        {
          "id": "b792e883-c5c1-4cdd-971a-da06f9c58d76",
          "name": "createWebACL",
          "request": {
            "url": "http://example.com/api/?Action=CreateWebACL?ChangeToken=ChangeToken&DefaultAction=DefaultAction&MetricName=MetricName&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates a WebACL, which contains the Rules that identify the CloudFront web requests that you want to allow, block, or count."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c494321c-7ffa-43a2-87c8-9a70d5a710b2"
            }
          ]
        },
        {
          "id": "6fa578d3-8896-4809-bd26-63fac45be0e5",
          "name": "deleteWebACL",
          "request": {
            "url": "http://example.com/api/?Action=DeleteWebACL?ChangeToken=ChangeToken&WebACLId=WebACLId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a561b840-f309-4e26-baf6-f28372e74f93"
            }
          ]
        },
        {
          "id": "7532d605-e3a4-4a2f-ab8a-437162d7d7e0",
          "name": "disassociateWebACL",
          "request": {
            "url": "http://example.com/api/?Action=DisassociateWebACL?ResourceArn=ResourceArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAF RegionalRemoves a web ACL from the specified resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e7768fee-c71d-4606-866b-93c68e9d49ba"
            }
          ]
        },
        {
          "id": "d4c89b4f-c85d-4441-b651-d348ece7598b",
          "name": "getWebACL",
          "request": {
            "url": "http://example.com/api/?Action=GetWebACL?WebACLId=WebACLId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96a29dc6-0ce4-49db-beae-571364b2ac02"
            }
          ]
        },
        {
          "id": "70d3d599-6b06-4662-9c60-609a0b9c1c79",
          "name": "getWebACLForResource",
          "request": {
            "url": "http://example.com/api/?Action=GetWebACLForResource?ResourceArn=ResourceArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAF RegionalReturns the web ACL for the specified resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b133bcea-dfcf-4239-920f-738a14c5a208"
            }
          ]
        },
        {
          "id": "6932d90b-63f1-40e7-843b-faaa4a1df4ba",
          "name": "listResourcesForWebACL",
          "request": {
            "url": "http://example.com/api/?Action=ListResourcesForWebACL?WebACLId=WebACLId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAF RegionalReturns an array of resources associated with the specified web ACL."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c54f98e5-6bbc-46b2-9210-bd6e26f1d3b7"
            }
          ]
        },
        {
          "id": "68764294-8782-4695-a38e-3b4f22b8de14",
          "name": "listWebACLs",
          "request": {
            "url": "http://example.com/api/?Action=ListWebACLs?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4bbea81d-f4d0-4c4c-95b5-bc91aa0a9abf"
            }
          ]
        }
      ]
    },
    {
      "name": "Byte Match Set",
      "item": [
        {
          "id": "5f9d446f-28d7-43ae-a89b-1a1101fd95e2",
          "name": "createByteMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateByteMatchSet?ChangeToken=ChangeToken&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates a ByteMatchSet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ecb2129a-62c2-47a4-ae6b-67aa2b9a442a"
            }
          ]
        },
        {
          "id": "3f02b8a3-a92a-4a3e-b0d7-cecfebdc1c3a",
          "name": "deleteByteMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteByteMatchSet?ByteMatchSetId=ByteMatchSetId&ChangeToken=ChangeToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5293c3f0-d1c6-40fd-bb48-a51d5872d73f"
            }
          ]
        },
        {
          "id": "a8c02754-f830-457b-8c88-396134a752d0",
          "name": "getByteMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=GetByteMatchSet?ByteMatchSetId=ByteMatchSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d5328bc-c7f1-4588-99e7-0d064ada9e50"
            }
          ]
        },
        {
          "id": "723d5a86-fbb2-45ec-94c4-bbb411158c1a",
          "name": "updateByteMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=UpdateByteMatchSet?ByteMatchSetId=ByteMatchSetId&ChangeToken=ChangeToken&Updates=Updates",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFInserts or deletes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "540b6991-ccdb-4e50-a594-880bbf1328c1"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Sets",
      "item": [
        {
          "id": "207bc1f6-0bb0-43c4-811f-8c3a1b635f96",
          "name": "createIPSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateIPSet?ChangeToken=ChangeToken&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates an."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3f9fd03d-d921-4f1b-a2e7-33d8a7e3b6a8"
            }
          ]
        },
        {
          "id": "b51de0c2-0bc6-45ce-8744-112a69b19c6d",
          "name": "deleteIPSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteIPSet?ChangeToken=ChangeToken&IPSetId=IPSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes an."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cf787ff3-179f-4bdf-8572-a7f5a222d34f"
            }
          ]
        },
        {
          "id": "16273216-2111-4249-80e6-797d8262f03e",
          "name": "getIPSet",
          "request": {
            "url": "http://example.com/api/?Action=GetIPSet?IPSetId=IPSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d3b09360-5a61-4b6b-a5c8-7176335bf564"
            }
          ]
        },
        {
          "id": "7ce6ad27-2320-4cd0-a3f6-d371785a9dac",
          "name": "listIPSets",
          "request": {
            "url": "http://example.com/api/?Action=ListIPSets?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f5bfee40-f3ed-4737-949b-7d07a9fadeb0"
            }
          ]
        },
        {
          "id": "9a802af9-1305-473a-840a-02612788bdc7",
          "name": "updateIPSet",
          "request": {
            "url": "http://example.com/api/?Action=UpdateIPSet?ChangeToken=ChangeToken&IPSetId=IPSetId&Updates=Updates",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFInserts or deletes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0fc840bc-a5a8-4a3d-ba33-08081fab585a"
            }
          ]
        }
      ]
    },
    {
      "name": "Rules",
      "item": [
        {
          "id": "f75d9fb2-c5f4-40fe-a46a-bf150bd49b1d",
          "name": "createRule",
          "request": {
            "url": "http://example.com/api/?Action=CreateRule?ChangeToken=ChangeToken&MetricName=MetricName&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates a Rule, which contains the IPSet objects, ByteMatchSet objects, and \n\t\t\tother predicates that identify the requests that you want to block."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ee5dc2ec-679e-4e64-8abf-026ea0b7dbbe"
            }
          ]
        },
        {
          "id": "8c15173e-a5e7-490f-b963-c9503cd3ecd1",
          "name": "deleteRule",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRule?ChangeToken=ChangeToken&RuleId=RuleId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6ce0b9d1-4b8c-4e0a-8e81-58fdee918602"
            }
          ]
        },
        {
          "id": "3db99ae0-ff94-4797-adc5-73aa37e8b6f7",
          "name": "getRule",
          "request": {
            "url": "http://example.com/api/?Action=GetRule?RuleId=RuleId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b55091b-967c-4f67-ac55-ea076cc97a9f"
            }
          ]
        },
        {
          "id": "ea8897b7-86e5-4d1e-895b-c049f4bd5682",
          "name": "listRules",
          "request": {
            "url": "http://example.com/api/?Action=ListRules?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3b185990-7754-41c1-8c04-639af712a760"
            }
          ]
        },
        {
          "id": "b4639e0e-e67b-4e80-8bdb-8f9fc4e92c0a",
          "name": "updateRule",
          "request": {
            "url": "http://example.com/api/?Action=UpdateRule?ChangeToken=ChangeToken&RuleId=RuleId&Updates=Updates",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFInserts or deletes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b0be5609-2dc3-4921-9118-24122a573c8c"
            }
          ]
        }
      ]
    },
    {
      "name": "Size Constraint Set",
      "item": [
        {
          "id": "88ab08de-f651-478c-8ea5-50fd428e354a",
          "name": "createSizeConstraintSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateSizeConstraintSet?ChangeToken=ChangeToken&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates a SizeConstraintSet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f15d2a41-b0dd-4a12-99cb-c5153ae3d76b"
            }
          ]
        },
        {
          "id": "1520ed08-a2b8-480a-b272-85bdee9b31ca",
          "name": "deleteSizeConstraintSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSizeConstraintSet?ChangeToken=ChangeToken&SizeConstraintSetId=SizeConstraintSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d11970eb-8b84-4fd6-b3ab-a7e6ca3c4aee"
            }
          ]
        },
        {
          "id": "d903bcc1-5612-4740-b4fb-6ee864808c76",
          "name": "getSizeConstraintSet",
          "request": {
            "url": "http://example.com/api/?Action=GetSizeConstraintSet?SizeConstraintSetId=SizeConstraintSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a6167ae2-3637-42ff-a585-2a5527524ece"
            }
          ]
        },
        {
          "id": "d7a88601-845a-4df5-a80c-890b5c976d4a",
          "name": "updateSizeConstraintSet",
          "request": {
            "url": "http://example.com/api/?Action=UpdateSizeConstraintSet?ChangeToken=ChangeToken&SizeConstraintSetId=SizeConstraintSetId&Updates=Updates",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFInserts or deletes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a46f60e2-2fd0-48dd-bf96-557f505ca2a4"
            }
          ]
        }
      ]
    },
    {
      "name": "SQL Injection Match Set",
      "item": [
        {
          "id": "c6ecf980-4e41-4567-8a8e-4903ce782332",
          "name": "createSqlInjectionMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateSqlInjectionMatchSet?ChangeToken=ChangeToken&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "10a357ba-4fda-41ed-98c5-8b86e7392424"
            }
          ]
        },
        {
          "id": "6596e138-fc51-480d-9b53-14a3742b0e41",
          "name": "deleteSqlInjectionMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSqlInjectionMatchSet?ChangeToken=ChangeToken&SqlInjectionMatchSetId=SqlInjectionMatchSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aeb21d9b-bfbc-4197-977c-bd041c6adc13"
            }
          ]
        },
        {
          "id": "b7506449-9466-4f24-bce9-34d7a7c09a17",
          "name": "getSqlInjectionMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=GetSqlInjectionMatchSet?SqlInjectionMatchSetId=SqlInjectionMatchSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "47211efe-2987-4ec7-a483-70b137681dc2"
            }
          ]
        }
      ]
    },
    {
      "name": "XSS Match Set",
      "item": [
        {
          "id": "6ab27387-ca16-4b39-9767-da5068e478a3",
          "name": "createXssMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateXssMatchSet?ChangeToken=ChangeToken&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates an."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "97a69860-c3f5-4596-95de-f63edf49be4f"
            }
          ]
        },
        {
          "id": "9d58062a-1211-420f-96c0-6f1bb61cad76",
          "name": "deleteXssMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteXssMatchSet?ChangeToken=ChangeToken&XssMatchSetId=XssMatchSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes an."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "057abb56-bcfe-4c20-ac0b-b59ad37ce107"
            }
          ]
        },
        {
          "id": "ce3c2029-f9e3-412c-a453-e67495940a66",
          "name": "getXssMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=GetXssMatchSet?XssMatchSetId=XssMatchSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "07594689-d808-4680-9ddf-8b401a3a50b0"
            }
          ]
        },
        {
          "id": "a4692c0c-9c11-49da-92cf-eb5e0acbe9fa",
          "name": "listXssMatchSets",
          "request": {
            "url": "http://example.com/api/?Action=ListXssMatchSets?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fe53f093-749f-458e-9a8e-058ffa0772e0"
            }
          ]
        }
      ]
    },
    {
      "name": "Change Token",
      "item": [
        {
          "id": "59ede4e8-66c0-4640-95dd-85dc975eeab2",
          "name": "getChangeToken",
          "request": {
            "url": "http://example.com/api/?Action=GetChangeToken?ChangeToken=ChangeToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFWhen you want to create, update, or delete AWS WAF objects, get a change token and include the change token in the create, update, or delete request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d9500c08-e52d-4733-b0a0-551c1148df03"
            }
          ]
        },
        {
          "id": "0ed86823-d77b-418f-8066-dd2ed740194b",
          "name": "getChangeTokenStatus",
          "request": {
            "url": "http://example.com/api/?Action=GetChangeTokenStatus?ChangeToken=ChangeToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the status of a ChangeToken that you got by calling."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e7d57a84-ea82-464c-82f7-352a60188690"
            }
          ]
        }
      ]
    },
    {
      "name": "Folder",
      "item": [
        {
          "id": "0ea89080-0476-443a-9f73-174f85e7a764",
          "name": "getSampledRequests",
          "request": {
            "url": "http://example.com/api/?Action=GetSampledRequests?MaxItems=MaxItems&RuleId=RuleId&TimeWindow=TimeWindow&WebAclId=WebAclId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFGets detailed information about a specified number of requests--a sample--that AWS WAF randomly selects from among the first 5,000 requests that your AWS resource received during a time range that you choose."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "18240a89-3c45-40f8-b9c7-a7553330a293"
            }
          ]
        }
      ]
    },
    {
      "name": "Byte Match Sets",
      "item": [
        {
          "id": "c7019564-c418-4a39-acad-e2c908389b65",
          "name": "listByteMatchSets",
          "request": {
            "url": "http://example.com/api/?Action=ListByteMatchSets?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b3b91345-1380-4d0a-a01c-38a2d865da28"
            }
          ]
        }
      ]
    },
    {
      "name": "Size Constraint Sets",
      "item": [
        {
          "id": "6710c596-96ec-424b-92fc-2dc4f9f9ee54",
          "name": "listSizeConstraintSets",
          "request": {
            "url": "http://example.com/api/?Action=ListSizeConstraintSets?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ff6cc9b1-14f1-45c2-850c-f33d301e3535"
            }
          ]
        }
      ]
    },
    {
      "name": "SQL Injection Match Sets",
      "item": [
        {
          "id": "c7d59772-4e61-4c21-8e31-7d7b7a5a8db5",
          "name": "listSqlInjectionMatchSets",
          "request": {
            "url": "http://example.com/api/?Action=ListSqlInjectionMatchSets?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d4e37b37-0874-4d55-8a4f-f2698b710cdc"
            }
          ]
        }
      ]
    }
  ]
}