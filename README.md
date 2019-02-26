# awesome-php-trait

This repository provide many php trait usable in your symfony project.

All Trait are tested in Symfony 4.2, the Trait can posibbly work with lower version but we don't have tested.

Some Trait needs dependency, check linked ressource to install them.

This is the list and small description for each of them :
- ActiveTrait                               : Add boolean "Active" property to any entity.
- ArchivedTrait                             : Add boolean "Archived" property to any entity.
- CreatedAtTrait        (DoctrineExtension) : Add datetime "createdAt" & datetime "updatedAt" property to any entity. The property is set and updated automatically each time you edit your entity.
- CreatedByTrait        (DoctrineExtension) : Add User "createdBy" & User "updatedBy" property to any entity. The property is set and updated automatically each time you edit your entity. ⚠ If your user entity is named differently you will need to edit the Trait.
- DeletedTrait                              : Add boolean "Deleted" property to any entity.
- PublishedTrait                            : Add boolean "Published" property to any entity.
- SortablePositionTrait (DoctrineExtension) : Add integer "Position" property to any entity. The property is set and updated automatically each time you edit your entity. 

Dependency List :
- [DoctrineExtension](https://symfony.com/doc/master/bundles/StofDoctrineExtensionsBundle/index.html)