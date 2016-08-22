# names-list-in-R
Return the in a list the names of the data.table


function(base) { a = names(base)
a = as.data.frame(a)
print(a)
}
