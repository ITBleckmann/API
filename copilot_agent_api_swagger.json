{
  "swagger": "2.0",
  "info": {
    "title": "Copilot Agent API",
    "version": "v1"
  },
  "paths": {
    "/v1/chat": {
      "get": {
        "summary": "Chat with the Copilot Agent",
        "responses": {
          "200": {
            "description": "Successful response",
            "schema": {
              "type": "object",
              "properties": {
                "message": {
                  "type": "string"
                }
              }
            }
          }
        }
      }
    },
    "/v1/suggest": {
      "get": {
        "summary": "Get suggestions from the Copilot Agent",
        "responses": {
          "200": {
            "description": "Successful response",
            "schema": {
              "type": "object",
              "properties": {
                "suggestions": {
                  "type": "array",
                  "items": {
                    "type": "string"
                  }
                }
              }
            }
          }
        }
      }
    },
    "/v1/refer": {
      "get": {
        "summary": "Refer to the Copilot Agent knowledge base",
        "responses": {
          "200": {
            "description": "Successful response",
            "schema": {
              "type": "object",
              "properties": {
                "references": {
                  "type": "array",
                  "items": {
                    "type": "string"
                  }
                }
              }
            }
          }
        }
      }
    }
  }
}