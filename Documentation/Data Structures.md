The following is pseudo-code of the structure:

Governing Body: {
  metadata: {
    name,
    officer positions: [
      {
        position: string,
        duties: extended string,
        term: string,
        elected by: committee
      }
    ]
  },
  committees: [
      {
        name: string,
        chair: member,
        mandate: extended string,
        members: [array]
      }
  ],
  members: [
    {
      id: number,
      [
        fields provided by Governing Body? How does this work?
      ]
  ],
  convenings: [
    {
      committee,
      sessions: [
        {
          start date:
        }
      ]
    }
  ]
}
