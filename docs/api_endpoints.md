HTML endpoints
  Root
    GET / triggers React components to load

JSON endpoints
  Users
    POST /api/users
    GET /api/users

  Session
    POST /api/sessions
    GET /api/sessions
    DESTROY /api/sessions

  Languages
    GET /api/languages

  Nodes
    GET /api/languages/:languageId/nodes
      accepts node[language_id] as a param
    GET /api/languages/:languageId/nodes/:nodeId
      accepts node[language_id] and node[id] as params