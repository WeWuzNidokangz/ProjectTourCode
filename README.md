# Operation Tour Code

**Introduction**

------------------------------------------------------------------------

This is a project for managing and distributing tour codes that specify dynamic (off-server) formats for [Pokémon Showdown][1], such as those used for [OM Mashups][2] metagames.

GitHub has many advantages over more basic tools for tour code managment, like Pastebin:-

- Each format has its tour code stored at a fixed and descriptive URL (e.g. [https://raw.githubusercontent.com/TheNumberMan/OperationTourCode/master/mashups/official/gen8staaabmons.tour][3] for [Gen 8] STAAABmons), not a throwaway URL with an arbitrary ID. These links can be trusted to contain official and generally up-to-date banlists.

- Source control provides a commented history of changes to enable an understanding of specifically where, when and why alterations to codes were made, such as [balance updates][4] and [fixing mistakes][5]. If a new version of a tour code introduces errors, there is a safe record of previous versions to rollback to. If a tour code stops working properly due to changes in the Pokémon Showdown server program, there is better evidence about what version it worked with to help investigate what happened.

- Operation Tour Code in particular structures the tour codes in standardized hierarchies with explanatory metadata that can be used by tools such as bots and web applications to easily access the data for purposes such as automated tour creation.

  [1]: http://pokemonshowdown.com/
  [2]: https://www.smogon.com/forums/threads/om-mashup-megathread.3657159/
  [3]: https://raw.githubusercontent.com/TheNumberMan/OperationTourCode/master/mashups/official/gen8staaabmons.tour
  [4]: https://github.com/TheNumberMan/OperationTourCode/commit/29acc40dc4770c64c4c2af507926249557ce5dc7
  [5]: https://github.com/TheNumberMan/OperationTourCode/commit/5cc97bbea63a3a6f9817af642aa761f39401ee3f
  [6]: https://github.com/TheNumberMan/OperationTourCode/commit/926d60b87418289e1c1f7b44fcaae9e9df13674e