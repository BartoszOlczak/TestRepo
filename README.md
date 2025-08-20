# TestRepo
Just to see how will synch work

# Code check
useEffect(() => {
  fetch('/api/users')
    .then(res => res.json())
    .then(data => setUsers(data))
}, [])

